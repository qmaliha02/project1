package application;
	
import javafx.application.Application;
import javafx.collections.FXCollections;
import javafx.collections.ObservableList;
import javafx.geometry.Insets;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.control.ComboBox;
import javafx.scene.control.Label;
import javafx.scene.control.TableColumn;
import javafx.scene.control.TableView;
import javafx.scene.control.TextField;
import javafx.scene.control.cell.PropertyValueFactory;
import javafx.scene.layout.HBox;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;

import java.io.FileInputStream;
import java.io.FileNotFoundException;
import java.io.IOException;
import java.sql.*;
import java.time.LocalDate;
import java.util.ArrayList;
import java.util.Properties;
import javafx.scene.control.DatePicker;
import javafx.stage.Stage;
import javafx.scene.Scene;
import javafx.scene.layout.BorderPane;


public class Main extends Application {
	public static void main(String[] args) {
		launch(args);
	}
	
	@Override
	public void start(Stage primaryStage) throws SQLException, ClassNotFoundException {
		try {
			primaryStage.setTitle("SUN LAB Accesss");
			
			
			TextField data = new TextField();
			Button buttonsubmit = new Button("Enter");
			
			buttonsubmit.setOnAction( e -> validate(data) );
			
			VBox vbox = new VBox(10);
			vbox.setPadding(new Insets(30,30,30,30));
			vbox.getChildren().addAll(data, buttonsubmit);
			
			Scene scene = new Scene(vbox, 400,400);
			primaryStage.setScene(scene);
			primaryStage.show();
			
			
			
		} 
		
		
		
		catch(Exception e) {
			e.printStackTrace();
		}
	}

	private void validate(TextField test) {
		try {
			
			int result = Integer.parseInt(test.getText());
			
			
	} catch(NumberFormatException e) {
		
		System.out.println("Invalid input");
		
		}
	}
	
	
}

