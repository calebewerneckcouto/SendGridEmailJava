## SendGrid API

- **POST /send-email**
  - Description: Sends an email using SendGrid API
  - Request Body: 
    ```json
    {
      "to": "recipient@example.com",
      "subject": "Subject of the Email",
      "content": "Content of the Email"
    }
    ```
  - Response:
    - Status: 200 OK
    - Body: 
      ```json
      {
        "message": "Email sent successfully"
      }
      ```
  - Error Response:
    - Status: 400 Bad Request
    - Body:
      ```json
      {
        "error": "Invalid request body"
      }
      ```
      
