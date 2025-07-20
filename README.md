<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Reservation Cancellation Form</title>
</head>
<body>
  <h1>Reservation Cancellation Form</h1>

  <form action="/cancel-reservation" method="post">

    
    <label for="email">Registered Email:</label>
    <input type="email" id="email" name="email" required><br><br>

   
    <label for="password">Account Password:</label>
    <input type="password" id="password" name="password" required><br><br>

  
    <label for="reservationNumber">Reservation Number:</label>
    <input type="number" id="reservationNumber" name="reservationNumber" required><br><br>

  
    <label for="reservationDate">Reservation Date:</label>
    <input type="date" id="reservationDate" name="reservationDate" required><br><br>


    <label for="reason">Reason for Cancellation:</label><br>
    <textarea id="reason" name="reason" rows="4" cols="40" placeholder="Write your reason here..."></textarea><br><br>

   
    <label for="type">Type of Reservation:</label>
    <select id="type" name="type">
      <option value="hotel">Hotel</option>
      <option value="flight">Flight</option>
      <option value="train">Train</option>
      <option value="bus">Bus</option>
    </select><br><br>

 
    <label>
      <input type="checkbox" name="agree" required>
      I agree to the cancellation policy and terms & conditions
    </label><br><br>

 
    <button type="submit">Cancel Reservation</button>

  </form>
</body>
</html>
