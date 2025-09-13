# AlphaBase One

**Effortless Sales Management for Every Business**

AlphaBase One is a comprehensive JavaFX-based sales management application designed for retail operations. It provides complete business management capabilities including inventory management, customer relationships, supplier management, sales tracking, and financial reporting.

## 🌟 Features

### Core Functionality
- **Multi-Language Support**: Kurdish, Arabic, and English
- **Inventory Management**: Complete stock control with warehouse support
- **Customer Management**: Track customer information and purchase history
- **Supplier Management**: Manage supplier relationships and purchasing
- **Sales Tracking**: Comprehensive sales reporting and analytics
- **Financial Reporting**: Detailed financial insights and reports

### Advanced Features
- **Automatic Updates**: Built-in update checking and notification system
- **Service Management**: Computer repair, car repair service workflows
- **Multi-Currency Support**: Dinar and Dollar currency handling
- **Barcode Support**: Product scanning and barcode generation
- **Receipt Printing**: A4 and thermal printer support
- **Backup & Restore**: Database backup and restore functionality

### Technical Features
- **Modern UI**: AtlantaFX theming with responsive design
- **Database**: MySQL integration with connection pooling
- **Modular Design**: Configurable features through SettingBean
- **Cross-Platform**: Works on Windows, macOS, and Linux

## 📋 System Requirements

- **Operating System**: Windows 10+, macOS 10.14+, or Linux
- **Java**: JDK 11 or higher
- **Database**: MySQL 5.7+ or MariaDB 10.2+
- **Memory**: 4GB RAM minimum, 8GB recommended
- **Storage**: 2GB available space

## 🚀 Installation


## 🔧 Configuration

The application uses a flexible configuration system:

- **Settings**: `app/tableview/*.properties` - UI component settings
- **Themes**: `app/theme/theme.properties` - Theme configuration  
- **Network**: `app/ip/ipaddress.properties` - Database connection settings
- **Updates**: `app/update/update.properties` - Update check settings

## 🏗️ Building from Source

### Prerequisites
- JDK 23 or higher
- Maven 3.6+
- Git

### Build Steps
```bash
# Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/alphabase-one.git
cd alphabase-one

# Build the application
mvn clean package

# Run the application
java -jar target/alphabase.jar
```

### Create Distribution Package
```bash
# Build Windows MSI package preparation
./build-simple-msi.sh

# Package will be created in target/msi-package/
```

## 📖 Usage

### First Run
1. **Language Selection**: Choose your preferred language (Kurdish/Arabic/English)
2. **Database Setup**: Configure MySQL connection settings
3. **User Creation**: Create your admin account
4. **Business Setup**: Configure your business information

### Daily Operations
- **Sales**: Use the POS interface for customer transactions
- **Inventory**: Add/edit products, manage stock levels
- **Reports**: Generate sales reports, inventory reports, financial summaries
- **Customers**: Manage customer information and purchase history

## 🔄 Updates

AlphaBase One includes automatic update checking:
- **Automatic Checks**: Checks for updates on startup (configurable)
- **Manual Checks**: Use Help → About → Check for Updates
- **Notifications**: Get notified when new versions are available
- **Easy Updates**: Direct links to download latest versions

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- **Email**: Karokh@Gmail.com
- **WhatsApp**: +964-750-328-7900, +964-770-697-7873
- **Telegram**: @karokhaziz


## 🏷️ Version History

- **v2.5** - Current version with update management system
- **v2.4** - Enhanced inventory management
- **v2.3** - Service management features
- **v2.2** - Multi-language support improvements
- **v2.1** - Database optimization and bug fixes
- **v2.0** - Major UI overhaul with AtlantaFX

## 🙏 Acknowledgments

- **AtlantaFX** - Modern JavaFX theming
- **JasperReports** - Report generation
- **MySQL** - Database management
- **FontAwesome & Ikonli** - Icon libraries

---

**AlphaBase One** - Empowering businesses with efficient sales management since 2021.
