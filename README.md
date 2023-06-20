# Table Reservation 

## Programmed by :

1. Savio Philip (22112333):https://github.com/saviophilip
2. Mathews Joe (22112348):https://github.com/mathewsjoe
## Description 

The project allows users to register, login, select a restaurant, make a reservation, and cancel a reservation. It handles user authentication, reservation availability, and storage of user credentials and reservation details in CSV files.

## Features 

* Registration and Login:
  The code allows users to register by providing a username and password.
  User credentials are stored in a CSV file (user_credentials.csv).
  Existing users can log in with their credentials.
* Restaurant Reservation:
  Users can make a reservation at a selected restaurant.
  Restaurant details are read from a CSV file (book_table.csv).
* Reservation cancellation policy:
  The Users can cancel a reservation by providing the reservation ID.
  Reservations are retrieved from the CSV file and checked for a matching reservation ID.
  If found, the reservation is canceled and removed from the reservations list.
  A confirmation message is displayed for successful cancellation.

## Functionality

* read_user_credentials_from_csv(): Reads the user credentials from the user_credentials.csv file.
* register_user(user_credentials): Registers a new user and adds their credentials to the user_credentials.csv file.
* is_username_taken(user_credentials, username): Checks if a username is already taken.
* is_valid_password(password): Checks if a password meets the criteria: at least 1 capital letter, 1 digit, and length more than 4.
* login(user_credentials): Logs in the user by verifying their credentials.
* read_restaurants_from_csv(): Reads the restaurant details from the restaurants.csv file.
* select_restaurant(restaurants): Displays the list of restaurants and allows the user to select one.
* cancel_reservation(reservation_id): Cancels a reservation.
* main(): The main function tkes care of the overall functionality of the hotel reservation system.

## Usage/ How to run the project ? 

1. Clone the repository or download the required files which are needed
2. Run the application by executing a certain code in your terminal:
   code - python restaurant_reservation.py
3. certain options will be presented to the user and he/she should choose the option
4. (i) Option 1: Register/Login
       * If you already have an account, choose "yes" to login.
       * If you don't have an account, choose "no" to register and create a new account.
5. (ii) Option 2: Make a Reservation
       * Select a restaurant from the list.
       * Enter the reservation details such as date, time, name, and number of people.
       * after this is done you will get the confirmation.
6. (iii) Option 3: Cancellation of the Reservation
       * Enter the reservation ID to cancel the reservation.
       * Once this is done the user will get confirmation on the cancellation made.
7. (iv) Option 4: Exit
       * Choose this option to exit the application.

## Sample Output 

### Registration successfull 
 <img width="1066" alt="Screenshot 2023-06-20 at 6 18 42 PM" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/0cfaafb1-95a8-4667-a32d-c10849bf620a">

### Login successfull 
 <img width="869" alt="Screenshot 2023-06-20 at 6 19 31 PM" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/a224a702-d825-4ce9-a663-1417b6d750a4">

### Reservation 
<img width="879" alt="Screenshot 2023-06-20 at 6 48 06 PM" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/f33cfdc2-d861-4075-b21d-987ed58c4a61">

### Exit
<img width="943" alt="Screenshot 2023-06-20 at 6 55 45 PM" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/05ee37b5-4cd2-4c49-aa4a-4f32caa1f3ab">

### DIrect Login (already registered)
<img width="945" alt="Screenshot 2023-06-20 at 6 57 17 PM" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/60e24cdc-546f-4ae2-99fb-f6f755b4c280">

### Cancellation 
<img width="941" alt="Screenshot 2023-06-20 at 6 52 05 PM 1" src="https://github.com/saviophilip/Table-Reservation-/assets/118896906/756b8ddc-aa78-4e4e-9cc6-1237019c35ad">



  
