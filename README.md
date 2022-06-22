# Weather-App-Group-Project- (NEW)

**Group Members**
1. Maisarah Binti Ishak (2013112)
2. Siti Husna Mohd Zubir (1816922)
3. Wan Muhammad Izzat Bin Wan Abd Ghapar

**Summary of Project**

This is a weather app that tracks the temperature, weather, humidity, and wind speed of a location in Malaysia. Based on the default interface, the system tracks the weather details in Selangor. There is no feature to track other location/city's weather details through the UI, so user needs to hard code the location in order to find out the weather details.

If you want to locate another city please follow this instruction:

Line 27:

http.Response response = await http.get(Uri.parse('https://api.openweathermap.org/data/2.5/weather?q=Selangor&units=metric&appid=fada61b32178ac7239e001419abf4362'));

- Change the location/city name on the api link from line 27 in main.dart
- Delete 'Selangor' from the link and change the location to any city in Malaysia
- E.g http.Response response = await http.get(Uri.parse('https://api.openweathermap.org/data/2.5/weather?q=Kuala&Lumpur&units=metric&appid=fada61b32178ac7239e001419abf4362'));
- From this example, the weather details from Kuala Lumpur will be displayed. 

**Objective of Project**
- To create a weather app that tracks down weather details for certain locations in Malaysia
- To verify the user's email address using firebase authentication
