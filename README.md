# RPA-EX---11
### NAME : ADHITHYA A
### REG NO : 212222220004
## AIM:
   To display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.

## ALGORITHM:
1. Get API Key from a weather provider (e.g., OpenWeatherMap).
2. Use Input Dialog to get the city name.
3. Create the API endpoint URL:
Example:
"https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric"
4. Use the HTTP Request activity:
* Method: GET
* URL: The full endpoint above
* Set Output to a variable (e.g., responseWeather)
5. Use Deserialize JSON to parse responseWeather.
6. Extract values like:
* Temperature: jsonObject("main")("temp").ToString
* Description: jsonObject("weather")(0)("description").ToString
7. Display the result in a Message Box.

## Program:
![Screenshot 2025-05-05 073703](https://github.com/user-attachments/assets/f4031a76-3a81-4717-bfdf-31f8ea1ee425)

![Screenshot 2025-05-05 073728](https://github.com/user-attachments/assets/dccd1160-ca40-45a5-ba66-d5c119e295d4)

## OUTPUT:
![Screenshot 2025-05-05 073745](https://github.com/user-attachments/assets/33dc38a5-9632-4568-93a8-ad9b91299bd1)

![Screenshot 2025-05-05 073754](https://github.com/user-attachments/assets/5046f835-be14-49c3-9da2-6c9bc6382b6d)

## RESULT:
   Hence we display a Welcome Message based on the user's role or name using If and Switch conditions in UiPath.

