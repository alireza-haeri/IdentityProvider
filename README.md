# 🚀 IdentityProvider: An Educational Project Series

> An educational journey into the core concepts of Authentication and Authorization in the .NET ecosystem.

[![Status](https://img.shields.io/badge/Status-Educational-blue.svg)](https://github.com/alireza-haeri/IdentityProvider)
[![Technology](https://img.shields.io/badge/Tech-C%23%20%7C%20.NET-blueviolet.svg)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](/LICENSE)

<br>

## 🎯 About This Project

This repository was created with the primary goal of **deeply learning and implementing the fundamental concepts of Authentication and Authorization** within the .NET ecosystem. Instead of a single application, this is a collection of several small, independent projects, each demonstrating a specific scenario or technique.

This is not a production-ready solution but rather a **learning playground** designed to explore the challenges and solutions in web application security.

---

## ✨ Covered Concepts & Techniques

Each folder inside `src/` is a self-contained, runnable project focusing on a specific concept:

#### 📂 `IdentityProvider.Basic`
*   **Topic:** Introduction to `Claims` and `ClaimsIdentity`.
*   **Description:** This project demonstrates the most fundamental form of identity in .NET. It covers how user information (like username, roles, etc.) is stored as `Claims` and accessed throughout an application.

#### 📂 `IdentityProvider.Authentication`
*   **Topic:** Implementing a Custom Authentication scheme.
*   **Description:** Here, we build a custom `Authentication Handler` from scratch. This gives us full control over the authentication process, independent of built-in mechanisms.

#### 📂 `IdentityProvider.Identity`
*   **Topic:** Using the powerful `ASP.NET Core Identity` framework.
*   **Description:** A complete implementation of user registration, login, user management, and roles using Microsoft's standard and comprehensive solution.

#### 📂 `IdentityProvider.Jwt` (includes `Symmetric` and `Asymmetric`)
*   **Topic:** Working with JSON Web Tokens (JWT).
*   **Description:**
    *   **Symmetric:** Demonstrates creating and validating JWTs using a symmetric key (a single shared key for signing and validation).
    *   **Asymmetric:** Implements a more secure approach using asymmetric keys (a Public/Private key pair) for issuing and validating tokens.

#### 📂 `IdentityProvider.AuthenticationWithAuthorization`
*   **Topic:** Implementing fine-grained access control (Authorization).
*   **Description:** After a user is authenticated, this project shows how to manage their access to different parts of the application using `Policy-Based Authorization` and custom `Authorization Handlers`.

#### 📂 `IdentityProvider.OAuth`
*   **Topic:** Introduction to the `OAuth 2.0` workflow.
*   **Description:** A simplified project to understand the basic concepts of the OAuth protocol and how it's used to grant access to third-party services without sharing user credentials.

---

## 🛠️ Core Technologies
*   **C#** & **ASP.NET Core**
*   **ASP.NET Core Identity**
*   **JWT (JSON Web Tokens)**
*   **Claim-Based & Policy-Based Authorization**

---

## 🚀 How to Run and Explore

The primary purpose of this repository is learning. To explore a specific concept:

1.  Clone the repository:
    ```sh
    git clone https://github.com/alireza-haeri/IdentityProvider.git
    ```
2.  Navigate to the specific project folder you want to explore within the `src/` directory:
    ```sh
    # For example, to run the Basic project:
    cd src/IdentityProvider.Basic
    ```
3.  Run the project:
    ```sh
    dotnet run
    ```
4.  Explore the code and experiment by making changes. Each project is designed to be as simple and focused as possible.

---

## 📫 Contact

If you have any questions or suggestions for improving this educational collection, I'd be happy to hear from you.

*   **Email:** alireza.haeri.dev@gmail.com
*   **Telegram:** [@AlirezaHaeriDev](https://t.me/AlirezaHaeriDev)
*   **LinkedIn:** [in/alireza-haeri-dev](https://www.linkedin.com/in/alireza-haeri-dev)
