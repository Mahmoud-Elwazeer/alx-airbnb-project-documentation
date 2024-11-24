# **🛠️ Technical Requirements**

# **1. Database Management**

- Use a relational database such as **PostgreSQL** or **MySQL**.
- Required tables:
    - Users (guests and hosts)
    - Properties
    - Bookings
    - Reviews
    - Payments

# **2. API Development**

- Use **RESTful APIs** to expose backend functionalities to the frontend.
- Include proper HTTP methods and status codes for:
    - GET (retrieve data)
    - POST (create data)
    - PUT/PATCH (update data)
    - DELETE (remove data)
- Use **GraphQL** for complex data fetching scenarios (optional but recommended).

# **3. Authentication and Authorization**

- Use **JWT** for secure user sessions.
- Implement role-based access control (RBAC) to differentiate permissions between:
    - Guests
    - Hosts
    - Admins

# **4. File Storage (Scenario based)**

- Store property images and user profile photos in cloud storage solutions such as **AWS S3** or **Cloudinary**. For implementation, we will use file storage

# **5. Third-Party Services**

- Use email services like **SendGrid** or **Mailgun** for email notifications.

# **6. Error Handling and Logging**

- Implement global error handling for APIs.