# My Ghost Blog

A modern, self-hosted blog powered by [Ghost](https://ghost.org/), a professional publishing platform.

## 🚀 Quick Start

### Prerequisites
- Node.js 18 or higher
- npm or yarn
- Ghost CLI (`npm install -g ghost-cli`)

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/ipanagiv/ghost.git
cd ghost
```

2. Start Ghost in development mode:
```bash
ghost start
```

3. Access your blog:
- Blog: http://localhost:2368
- Admin Panel: http://localhost:2368/ghost/

### Useful Commands
- `ghost start` - Start your Ghost instance
- `ghost stop` - Stop your Ghost instance
- `ghost restart` - Restart your Ghost instance
- `ghost update` - Update Ghost to the latest version
- `ghost ls` - List all Ghost instances

## 📁 Project Structure
```
ghost/
├── content/          # Content files (posts, images, themes)
├── current/          # Current Ghost installation
├── versions/         # Ghost version files
└── config.*.json     # Environment-specific configurations
```

## 🛠️ Configuration
- Development configuration is in `config.development.json`
- Production settings should be configured in `config.production.json`
- Environment variables can be set in `.env` files

## 🔒 Security
- Sensitive data and credentials are excluded via `.gitignore`
- Environment-specific configurations should not be committed
- SSL certificates should be configured for production

## 📝 Content Management
1. Navigate to http://localhost:2368/ghost/
2. Create your admin account on first run
3. Start creating and publishing content!

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support
For issues and questions:
- Check [Ghost Documentation](https://ghost.org/docs/)
- Visit [Ghost Forum](https://forum.ghost.org/)
- Open an issue in this repository 