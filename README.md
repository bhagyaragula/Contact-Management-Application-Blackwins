API Endpoints:
1. GET /contacts
○ Fetch a list of all contacts.
○ Each contact should include:
■ Contact ID
■ Name
■ Email
■ Phone Number
■ Address (Optional)
■ Created At (Timestamp)

2. POST /contacts
○ Create a new contact.
○ Input field
■ Name
■ Email

■ Phone Number
■ Address (Optional)
○ Return the newly created contact with a unique Contact ID.
3. PUT /contacts/:id
○ Update an existing contact based on its ID.
○ Input field
■ Name
■ Email
■ Phone Number
■ Address (Optional)
○ Ensure data validation for required fields and proper error handlin
4. DELETE /contacts/:id
○ Delete a contact based on its ID.
○ Return a success message confirming the deletio
5. GET /contacts/:id
○ Fetch a single contact based on its ID.

Bonus Features (Optional):
● Search Contacts: Implement a feature that allows users to search contacts
by name or email.
● Validation: Ensure all required fields are validated properly (e.g., Nam
Email, Phone Number).
