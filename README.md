Viktorija Hadzieva 226081

2.![Untitled Diagram drawio (1)](https://github.com/Victori122/SI_lab2_226081/assets/165795358/11c6ea27-4eba-4eab-8747-4e0ea5edbb77)


3.Цикломатската комплексност на кодот е 10, ја добив со формулата P+1,каде
Р е бројот на предикатно јазли.Во овој случај бројот на предиканти јазли е 9,
па 9+1 =10 ,каде 10 изнесува цикломатската комплексност

4. Item("Laptop", "1234567890", 800, 0.0),payment=800
  Item("Phone", "9876543210", 600, 0.15),payment=450
   Item("Book", "654321", 50, 0.1),payment=45
   Item("Watch", "01234", 400, 0.2),payment=300
 Item("Camera", "12B34", 300, 0.1),payment=270

5. T && F && X
 item.getPrice() > 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) = anything
T && T && F
 item.getPrice() > 300, item.getDiscount() > 0, item.getBarcode().charAt(0) != '0'
F && X && X
 item.getPrice() <= 300, item.getDiscount() = anything, item.getBarcode().charAt(0) = anything
T && T && T
 item.getPrice() >= 300, item.getDiscount() > 0, item.getBarcode().charAt(0) == '0'
F && F && X
 item.getPrice() <= 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) = anything
