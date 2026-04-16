Blood Link is a distributed platform designed to streamline blood request management by connecting doctors, blood banks and donors in real time.

The system enables fast coordination during blood shortages, improves donor mobilization, and ensures efficient tracking of blood requests from creation to fulfilment.

Features

Doctor
- Create blood requests (blood type, quantity)
- Send requests to multiple blood banks simultaneously
- Track request status in real time
- Automatically stop requests once fulfilled

Blood Bank
- Receive and respond to blood requests
- Fulfill requests directly from available stock
- Trigger donor alerts when stock is insufficient
- Independently launch donation campaigns

Donor
- Receive real-time alerts to blood requests
- Respond to donation requests
- Undergo eligibility verification before donation
- Maintain an updated medical and donation history

Notifications System
- Real time alerts to donors
- Status updates between doctors and blood banks

How It works
1. A doctor creates a blood request.
2. The request is sent to multiple blood banks
3. Each blood bank:
   - Supplies blood if available
   - Or sends alerts to thier affiliated donors if not
4. Donors respond to alerts and made a donation request
5. Donor eligibility is verified befor donation
6. Multiple blood banks can contribute to the same request.
7. Once the required quantity is reached, the request is automatically closed.


Tech Stack:
* Backend: Java, Spring Boot
* Database: MySQL
* Messagiing: RabbitMq for notifications
