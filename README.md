# lwiki

lwiki is a wiki-type website built using the Laravel framework in PHP. It allows users to create, edit, and collaborate on content in a collaborative and organized manner.

## Features

- **User Authentication**: Secure user authentication system allows users to sign up, log in, and manage their accounts.
- **Wiki Pages**: Users can create new wiki pages, edit existing ones, and view the revision history.
- **Revision History**: Each wiki page maintains a history of revisions, allowing users to track changes over time and revert to previous versions if needed.
- **Markdown Support**: Content is written in Markdown format, providing flexibility and ease of formatting.
- **Search Functionality**: Users can search for specific wiki pages or content within pages.
- **Permissions Management**: Administrators can manage user permissions, including editing and viewing restrictions.
- **Responsive Design**: The website is designed to be responsive, providing a seamless experience across devices of all sizes.

## Installation

1. Clone the repository:

```
git clone https://github.com/your_username/lwiki-aisle.git
```

2. Install dependencies:

```
cd lwiki-aisle
composer install
```

3. Set up the environment configuration:

```
cp .env.example .env
```

4. Generate an application key:

```
php artisan key:generate
```

5. Configure the database connection in the `.env` file.

6. Run the database migrations:

```
php artisan migrate
```

7. Start the development server:

```
php artisan serve
```

8. Visit `http://localhost:8000` in your web browser to access the application.

## Contributing

Contributions are welcome! Please follow the [Contribution Guidelines](CONTRIBUTING.md) when submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by [Wikipedia](https://www.wikipedia.org/).
- Special thanks to the Laravel community for their amazing contributions and support.