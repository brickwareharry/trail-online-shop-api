# Online Shop API

Welcome to the Online Shop API documentation! This guide will help you get started with building your own online shop using C# .NET 8.

## Prerequisites

Before you begin, make sure you have the following installed:

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio Code](https://code.visualstudio.com/) or any other preferred code editor

## (Under Construction) Building Procedure




## (Draft Template) Getting Started

To get started with the Online Shop API, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/online-shop-api.git
    ```

2. Navigate to the project directory:

    ```bash
    cd online-shop-api
    ```

3. Install the required dependencies:

    ```bash
    dotnet restore
    ```

4. Start the API server:

    ```bash
    dotnet run
    ```

5. Open your preferred API testing tool (e.g., [Postman](https://www.postman.com/)) and start making requests to `http://localhost:5000`.

## API Endpoints

The following endpoints are available in the Online Shop API:

- `GET /products`: Get a list of all products.
- `GET /products/{id}`: Get details of a specific product.
- `POST /products`: Create a new product.
- `PUT /products/{id}`: Update an existing product.
- `DELETE /products/{id}`: Delete a product.

For detailed information on how to use each endpoint, refer to the [API documentation](https://your-api-documentation-url).

## Authentication

To access certain API endpoints, you may need to authenticate your requests. Please refer to the [authentication documentation](https://your-authentication-documentation-url) for more information.

## Error Handling

In case of any errors, the API will return appropriate HTTP status codes along with error messages. Refer to the [error handling documentation](https://your-error-handling-documentation-url) for more details.

## Conclusion

Congratulations! You have successfully set up the Online Shop API and are ready to start building your own online shop. If you have any questions or need further assistance, please don't hesitate to reach out to our support team.

Happy coding!

## Reference notes

### GitHub Personal Access Tokens
GitHub introduced "Fine-grained tokens" as a more secure and customizable alternative to the classic personal access tokens. Here's a brief overview of both options:
#### Fine-grained Tokens
More Secure: Fine-grained tokens allow you to specify exact access levels and expiration dates for different areas of your GitHub account.
Customizable: You can create tokens with specific permissions for specific repositories, enhancing security by limiting access.
#### Tokens (Classic)
Broader Access: Classic tokens provide broader access, which might be simpler but less secure as they give wide-ranging permissions across all repositories.
Familiar Setup: The setup process is similar to the original personal access tokens and might be more familiar to many users.
#### Which to Choose?
If you need a token for general use and are comfortable with broad access, you might choose the Tokens (Classic). This is straightforward and covers general use cases.
If you require a more secure, tailored approach, especially for critical or sensitive projects, Fine-grained Tokens would be the better choice. This option allows you to limit the token's scope to exactly what is needed for specific tasks or projects.
Given your use case of pushing code to a GitHub repository, a fine-grained token might be preferable if you want to ensure that the token only has the necessary permissions. This can help mitigate potential risks if the token is ever compromised. Here’s how you can create a fine-grained token:

##### Creating a Fine-grained Token
1. Go to Fine-grained Tokens: Select the "Fine-grained tokens" option.
2. Create Token: Click on “Create token” or "New token".
3. Configure Permissions: Select the specific permissions you need, such as repo for repository access. You can also set an expiration date for the token, which is a recommended security practice.
4. Generate and Copy: Once configured, generate the token and make sure to copy and save it securely; you won't be able to see it again after you leave the page.

After creating the token, use it in the same way as described previously: when prompted for a password during Git operations, input the token instead.
