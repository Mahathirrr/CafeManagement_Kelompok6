# CoffeeShop Management GUI Application

This Java GUI application is a CoffeeShop management system. It allows users to select various coffee and pastry items, calculate the total price with tax, and generate a receipt.

## Disclaimer

Please note that the appearance or behavior of the program may vary between different operating systems. The application has been tested and is almost fine on **Linux**. It is highly recommended to try the application on a **Linux** system for the optimal experience.

## Project Overview

The project uses Java AWT and Swing libraries for the graphical user interface. It consists of the following components:

- `cafeguii.gui.Dashboard`: The main GUI class that displays the coffee shop interface.
- `cafeguii.app.CoffeeShopCalculator`: A class responsible for calculating the tax based on the subtotal.
- `cafeguii.menu.CoffeeShopItem`: A class representing coffee and pastry items with name, price, icon, and label.
- `cafeguii.images2/`: Directory containing images of coffee shop items used in the GUI.

## How to Use

1. Navigate to the `dist` directory.
2. Run the CoffeeShop GUI application by executing the following command in the terminal:

    ```bash
    java -jar CafeGuii.jar
    ```

3. Select items by checking the checkboxes and adjusting the quantity.
4. Click the "Total" button to calculate the total price with tax.
5. Optionally, print a receipt using the "Receipt" button.

## Application Preview

<p align="center">
  <img src="https://github.com/Mahathirrr/CoffeeShop/assets/111866202/5e37fa57-328f-47ca-9cdc-edb38149caf8" alt="CoffeeShop Dashboard" width="75%">
</p>

<p align="center">
  <em>CoffeeShop Dashboard displaying the coffee shop interface.</em>
</p>

## Contributors

### Kelompok 6

- Muhammad Mahathir (2208107010056)
- Azri Harniza (2208107010034)
- Muhammad Khalid AlGhifari (2208107010044)
- Pryta Rosela (2208107010046)
- Raihan Firyal (2208107010084)
- T.Farhansyah (2208107010090)
  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
