# Django Static Tags Fixer Plugin for PyCharm

![Django Logo](https://www.djangoproject.com/s/img/logos/django-logo-positive.png)

## Overview

The Django Static Tags Fixer Plugin for PyCharm is a powerful tool for Django developers that helps you easily fix missing static tags in your Django templates. It enhances your development workflow by automating the process of adding `{% load static %}` and `{% static 'path/to/your/file' %}` tags to your HTML templates, ensuring that your static assets are properly linked.

## Features

- **Automatic Detection**: The plugin scans your Django template files and detects missing `{% load static %}` and `{% static 'path/to/your/file' %}` tags.
- **Quick Fixes**: With a simple click, you can apply quick fixes to add the missing tags automatically.
- **Configurable**: You can configure the plugin to use your custom template tags or customize the way it adds the static tags.
- **Compatibility**: Works seamlessly with Django projects of any size and complexity.

## Installation

1. Open PyCharm.
2. Go to **File** > **Settings** (or **PyCharm** > **Preferences** on macOS).
3. In the settings dialog, navigate to **Plugins**.
4. In the Plugins settings, click on the **Marketplace** tab.
5. Search for "Django Static Tags Fixer" and click **Install**.
6. Restart PyCharm to activate the plugin.

## Usage

1. Open your Django project in PyCharm.
2. Open a Django template file that contains missing static tags.
3. The plugin will automatically detect missing static tags and highlight them.
4. Place your cursor over the highlighted code.
5. A light bulb icon will appear. Click on it to reveal the available quick fixes.
6. Select the desired fix to add the missing tags automatically.

## Configuration

You can customize the behavior of the Django Static Tags Fixer Plugin by going to **File** > **Settings** (or **PyCharm** > **Preferences** on macOS) and navigating to **Django Static Tags Fixer** in the settings. Here, you can:

- Specify your custom template tags for loading static files.
- Choose the format of the `{% static 'path/to/your/file' %}` tag.
- Configure whether to scan all Django template files or only those in specific directories.

## Contributing

We welcome contributions to the Django Static Tags Fixer Plugin for PyCharm! If you'd like to contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request with a clear description of your changes.

## Issues

If you encounter any issues or have suggestions for improvement, please [create a new issue](https://github.com/thearjun/django-static-tags-fixer-plugin/issues) on our GitHub repository.

## License

This plugin is released under the [MIT License](LICENSE.md).

## Credits

The Django Static Tags Fixer Plugin for PyCharm is developed and maintained by the community. Thank you to all contributors who make this plugin possible.

---

Happy coding with Django and PyCharm! If you find this plugin useful, please consider [buying us a coffee](https://www.buymeacoffee.com/arjunadhikari) to support its development.
