**UPI - Unified Payment Interface**

<img width="1414" height="1022" alt="Screenshot 2025-12-06 at 8 23 18 PM" src="https://github.com/user-attachments/assets/64387f36-d498-4ece-b795-f03218c4a825" />

Multiple Transfer Protocals are used in traditional banking system;
1) IMPS -> immediate Payment System
2) NEFT -> national elevtronic fund transfer
3) RTGS -> Real-Time Gross Settlement
4) UPI -> Unified Payment Interfact(Modern Era Banking System)

**How does UPI works?**

NPCI API -> National Payment Corporation of India ( which is a closed Protocol)
(Note that: This API only interact with trusted organisational bank(like: ICICI, HDFC, IDFC, YES Bank and many more.)

Basically, a normal person can't interact with NPCI directly.

Customer/ Reciever PSP( Payment Service provider) ->

it is a interface/middleware which contact Consumer to NPCI ( like: Gpay, PhonePe, Paytm has to partnered with trusted bank).

following each user has VPA -> virtual private Address( which is stored in the form of QR code)

format: username@UPI_handle -> these are stored in the VPA.

**Author: Manul Rastogi**
