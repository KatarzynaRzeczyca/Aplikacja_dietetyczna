
**Temat:** Aplikacja wspomagająca pracę dietetyka, której zadaniem jest gromadzenie danych pacjentów oraz wyników pomiarów masy ciała i współczynnika BMI
(Body Mass Index)wykonanych w kolejnych punktach czasowych. Dla wybranego pacjenta program ma generować wykresy zmienności obu tych parametrów
i wyznaczać ich proste statystyki (nim, max, średnia). Informacje należy przechowywać w relacyjnej bazie danych (np. JavaDB w trybie embedded) lub
pliku (sugerowane jest wykorzystanie standardowych formatów, np. XML lub JSON).

**Zespol:** Katarzyna Muter, Katarzyna Rzeczyca

**Biblioteki:** 
import java.awt.*;
import java.awt.event.*;
import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.util.ArrayList;
import java.util.Calendar;
import java.util.Date;

import javax.swing.*;
import javax.swing.event.ListSelectionEvent;
import javax.swing.event.ListSelectionListener;
import javax.swing.table.DefaultTableModel;
import com.toedter.calendar.JDateChooser;

import org.jfree.chart.ChartFactory;
import org.jfree.chart.ChartPanel;
import org.jfree.chart.JFreeChart;
import org.jfree.chart.plot.PlotOrientation;
import org.jfree.data.category.DefaultCategoryDataset;

**Uwagi dodatkowe:** Brak
