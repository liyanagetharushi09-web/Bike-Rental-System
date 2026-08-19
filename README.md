# Bike Rental System 

## Description
Bike Rental System is a console-based application developed in C++ for the CO1409 Programming module.  
It allows customers to manage credits, build bookings by selecting bikes, rental durations, and optional accessories, then checkout and view booking history.  
The program is menu-driven, fully validated, and demonstrates structured programming concepts, use of constants, arrays/vectors, functions, and clean code practices.  

## Features
- 💳 **Credit Management**: Add and maintain a balance of credits.
- 🚲 **Bike Selection**: Choose one or more bikes (Standard, Mountain, Electric).
- ⏱️ **Rental Duration**: Options include 1 Hour, Half Day, Full Day, Weekend.
- 🎒 **Accessories**: Optional add-ons such as Helmet, Lock, Camera Mount, Child Seat, Repair Kit, GoPro.
- 🧮 **Cost Calculation**: Computes total cost (bikes + duration + accessories).
- 📑 **Booking Summary**: Displays a detailed breakdown before checkout.
- ✅ **Checkout**: Validates credit balance, deducts cost, confirms booking.
- 📜 **Booking History**: Stores and displays all bookings made during the session.
- 🖥️ **Menu Interface**: Simple, validated menu with options to add credits, create bookings, view history, or exit.

## System Requirements
- Language: C++

## Usage
1. Follow the menu prompts:
- Add credits to start.
- Create bookings by selecting bikes, duration, and accessories.
- Checkout and confirm bookings.
- View booking history at any time.
- Exit when finished.

## Example Workflow
- User adds 20 credits.
- Selects 1 Mountain bike and 1 Electric bike.
- Chooses "Full Day" rental.
- Adds Helmet and Lock accessories.
- Program calculates total, validates credits, deducts cost, and confirms booking.
- Booking is stored in history and can be viewed later.

## Code Highlights
- **Constants**: All prices and menu sizes defined as constants (no magic numbers).
- **Structs**: Used for BikeSelection, AccessorySelection, and Booking to group related data.
- **Vectors**: Dynamic lists for bikes, accessories, and booking history.
- **Functions**: Modular design for input validation, selection, calculation, checkout, and history display.
- **Validation**: Ensures user inputs are numeric, within range, and positive where required.
- **Formatting**: Prices displayed with two decimal places for clarity.

## Assessment Notes
- Developed individually as per coursework requirements.
- Code is properly indented, commented, and uses meaningful variable names.
- Demonstration required in lab sessions.
- Academic integrity policies strictly apply.

--------------------------------
Developed for CO1409 Programming Coursework (Bike Rental System)  
University of Lancashire, Academic Year 2025-26
