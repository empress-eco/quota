<p align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
</p>

An essential utility for managing user, company, and space limitations in Empress. Explore the [documentation](https://empress.eco/), [report a bug](https://github.com/empress-eco/quota/issues), or [request a feature](https://github.com/empress-eco/quota/issues).

## About The Project

Empress Quota is a dedicated application designed to streamline the management of user, company, and space limitations within the Empress environment. It's an invaluable tool for administrators seeking an efficient way to control and monitor these aspects in their ERP system.

### 🌟 Key Features

- Manage active users and companies
- Control backup file sizes
- Set document limits and monitor usage
- Monitor private and public file sizes
- Set and view usage info

## Getting Started

### Prerequisites

You'll need Empress installed to use Empress Quota.

### Installation

Clone the repository and install the app with the following steps:

```sh
git clone https://github.com/empress-eco/quota.git
cd quota
bench get-app Empress_quota
bench --site *site_name* install-app Empress_quota
```

### Usage

After installation, Empress Quota will automatically add a quota configuration in the `site_config.json` file. You can manually change the default values to modify the limits. 

To view the Usage info, find it in the 'Settings' module or search 'Usage Info' in the awesome bar.

```json
{
 "quota": {
  "active_users": 6,
  "company": 2
 }
}
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Here's how you can contribute:

- **Fork the Project**: Click the 'Fork' button at the top right corner of this page.
- **Create your Feature Branch**: `git checkout -b feature/AmazingFeature`
- **Commit your Changes**: `git commit -m 'Add some AmazingFeature'`
- **Push to the Branch**: `git push origin feature/AmazingFeature`
- **Open a Pull Request**: Go to your repository and click the 'New pull request' button.

## License

This project is under the [MIT License](https://opensource.org/licenses/MIT). Your contributions are also welcomed under the MIT License.

## Acknowledgements

Special thanks to the [Empress Community](https://Empress.io/), the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.