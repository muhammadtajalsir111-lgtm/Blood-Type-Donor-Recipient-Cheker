# Blood-Type-Donor-Recipient-Cheker
A medical utility that asks if you want to donate or receive blood. It then asks for your specific blood type (e.g., +O, -AB) and instantly provides a list of all compatible donor or recipient blood types based on standard medical compatibility rules.
Blood-Type-Donor-Recipient-Checker
A medical utility that asks if you want to donate or receive blood. It then asks for your specific blood type (e.g., +O, -AB) and instantly provides a list of all compatible donor or recipient blood types based on standard medical compatibility rules.


Key Features
Donation Path: If you want to donate, simply enter your blood type, and the program instantly lists all compatible recipient types.
Receiving Path: If you need to receive blood, input your blood type to see a list of all safe donor types.
User-Friendly Input: Asks clear questions (yes / no) to guide you through the correct medical scenario.
Comprehensive Compatibility: Covers all major blood groups, including both positive (+) and negative (-) Rh factors.
How It Works
The program utilizes a types_of_blood() function and conditional logic (if, elif, else) to map your specific blood type to standard medical compatibility rules.

Donor logic: Determines which blood types can safely receive your blood (e.g., O- can donate to all types).
Recipient logic: Determines which blood types are safe to receive from (e.g., AB+ can receive from all types).
How to Run
Ensure Python 3 is installed on your machine.
Download the script (blood_type_checker.py).
Run it via your terminal:
python blood_type_checker.py
