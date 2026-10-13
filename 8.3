import javafx.application.Application;
import javafx.geometry.Insets;
import javafx.scene.Scene;
import javafx.scene.control.*;
import javafx.scene.layout.GridPane;
import javafx.stage.Stage;

public class TipCalculator extends Application {

    @Override
    public void start(Stage stage) {

        Label billLabel = new Label("Bill Amount:");
        TextField billField = new TextField();

        Label tipLabel = new Label("Tip Percentage:");
        Slider tipSlider = new Slider(0, 30, 15);
        tipSlider.setShowTickLabels(true);
        tipSlider.setShowTickMarks(true);

        Label tipValue = new Label("15%");

        Label resultLabel = new Label("Total Amount:");
        Label result = new Label("$0.00");

        Button calculate = new Button("Calculate");

        // Respond to slider interaction
        tipSlider.valueProperty().addListener((obs, oldValue, newValue) -> {
            tipValue.setText(String.format("%.0f%%", newValue.doubleValue()));
        });

        // Respond to button click
        calculate.setOnAction(e -> {
            try {
                double bill = Double.parseDouble(billField.getText());
                double tip = tipSlider.getValue();

                double tipAmount = bill * tip / 100;
                double total = bill + tipAmount;

                result.setText(String.format("$%.2f", total));
            }
            catch (NumberFormatException ex) {
                result.setText("Enter a valid amount");
            }
        });

        GridPane grid = new GridPane();
        grid.setPadding(new Insets(20));
        grid.setHgap(10);
        grid.setVgap(15);

        grid.add(billLabel, 0, 0);
        grid.add(billField, 1, 0);

        grid.add(tipLabel, 0, 1);
        grid.add(tipSlider, 1, 1);
        grid.add(tipValue, 2, 1);

        grid.add(calculate, 1, 2);

        grid.add(resultLabel, 0, 3);
        grid.add(result, 1, 3);

        Scene scene = new Scene(grid, 450, 250);

        stage.setTitle("Tip Calculator");
        stage.setScene(scene);
        stage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}
