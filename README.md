# Project Training with Composer and PSR-4 Autoloading

This project serves as a simple training ground to practice working with Composer and the PSR-4 autoloading standard. The goal is to provide a hands-on experience for setting up a project structure, managing dependencies with Composer, and leveraging PSR-4 autoloading for efficient class loading.

## Project Structure

The project follows a straightforward directory structure:

```
project-root/
│
├── src/
│   └── Hello.php
├── public/
│   └── index.php
│
├── .git/
├── .gitignore
├── composer.json
├── composer.lock
└── README.md
```

- **src/Hello.php:** This is a sample class file within the project, following the PSR-4 namespace and class naming conventions, with "Hello World" rendering by echo.

- **.gitignore:** This file includes the standard rules for ignoring files and directories that should not be tracked by version control.

- **composer.json:** The Composer configuration file where project dependencies and autoloading settings are defined.

## Getting Started

To get started with this project, follow these steps (if composer is in globally install, adapte this for you case):

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/KevinGIRAULT/composer-psr4-autoload.git
   cd composer-psr4-autoload/
   ```
2. **Check Composer Update:**
   ```bash
   composer self-update
   ```

3. **Install Dependencies:**
   ```bash
   composer install
   ```

4. **Autoloading with Composer:**
   The project is configured to use Composer's autoloader. You can now autoload classes using the following line in your project files:

   ```php
   require_once 'vendor/autoload.php';

   use App\MyClass;

   // Your code here...
   ```

## Contributing

If you have improvements, bug fixes, or additional features to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your modifications.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding!
