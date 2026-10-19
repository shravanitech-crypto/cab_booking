
# 🚖 Cab Booking Chatbot

## 📌 Project Overview
The Cab Booking Chatbot is a simple Python-based console application that allows users to book a cab by selecting a cab type and route. It calculates the total fare based on the distance and rate per kilometer. Users can confirm their booking and receive a randomly generated OTP or cancel the ride.

## ✨ Features
- 🚗 Multiple Cab Types: Auto, Sedan, and SUV.
- 📍 Predefined Routes: Choose from three available routes.
- 💰 Automatic Fare Calculation based on distance and cab rate.
- 🔐 Random OTP Generation for confirmed bookings.
- ❌ Ride Cancellation before OTP sharing.
- 🔄 Interactive Menu with input validation.
- 🛡️ Handles invalid cab, route, and menu choices.

## 🛠️ Technologies Used
- Python 3.
- Random Module.

## 🚕 Cab Rates

| Cab Type | Rate per Kilometer |
|---|---:|
| Auto | ₹12/km |
| Sedan | ₹18/km |
| SUV | ₹25/km |

## 📍 Available Routes

| Source | Destination | Distance |
|---|---|---:|
| Pune Station | Shivajinagar | 5 km |
| Swargate | Kothrud | 8 km |
| Hinjawadi | Wakad | 10 km |

## ⚙️ How to Run

1. Install Python 3 on your system.
2. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

3. Navigate to the project folder:

   ```bash
   cd cab-booking-chatbot
   ```

4. Run the Python program:

   ```bash
   python cab_booking.py
   ```

## 🧮 Fare Calculation

**Formula:**

Total Fare = Rate per Kilometer × Distance

**Example:**

If you select a Sedan for the Pune Station to Shivajinagar route:

- Rate: ₹18/km
- Distance: 5 km
- Total Fare: ₹18 × 5 = ₹90

## 🔐 Booking Process

1. Select the Book Ride option.
2. Choose a cab type.
3. Select a predefined route.
4. Review the ride details and total fare.
5. Confirm the booking to generate a four-digit OTP, or cancel the ride.
6. Exit the application when finished.

## 🎯 Learning Outcomes
- Using dictionaries to store structured data.
- Applying loops and conditional statements.
- Handling user input and validating choices.
- Performing arithmetic calculations.
- Generating random OTPs using Python's `random` module.
- Building an interactive command-line application.

## 🚀 Future Enhancements
- Add more routes and cab categories.
- Allow users to enter custom pickup and drop locations.
- Store booking history.
- Integrate a database for user and ride details.
- Develop a graphical user interface.
- Connect the application to a real mapping or cab booking service.


---

⭐ If you find this project useful, consider giving the repository a star!
