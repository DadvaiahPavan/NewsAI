# NewsAI - Modern News Aggregator

NewsAI is a modern, responsive news aggregation platform built with React, TypeScript, and Tailwind CSS. It provides users with a seamless experience to browse, search, and summarize news articles from various categories and sources worldwide.

![Web UI](https://i.ibb.co/KKMBZnY/Screenshot-2024-11-12-142759.png)
![Web UI](https://i.ibb.co/XLNfDST/Screenshot-2024-11-12-142840.png)



## 🌟 Features

- **Real-time News Updates**: Access the latest news articles from trusted sources
- **Category-based Navigation**: Browse news by categories including:
  - Top Headlines
  - Business
  - Technology
  - Health
  - Sports
  - Entertainment
  - Science

- **Smart Search**: Search for specific news topics with advanced filtering
- **AI-Powered Summaries**: Get quick, AI-generated summaries of articles
- **Multi-language Support**: Available in:
  - English
  - Spanish
  - French
  - German
  - Italian

- **International Coverage**: News from multiple countries including:
  - United States
  - United Kingdom
  - India
  - Canada
  - Australia

- **Modern UI/UX**: Beautiful, responsive design with smooth animations
- **Article Management**: Save and organize your favorite articles

## 🚀 Technologies Used

- **Frontend**:
  - React 18
  - TypeScript
  - Tailwind CSS
  - Framer Motion
  - React Router DOM
  - Axios
  - Lucide React Icons

- **APIs**:
  - NewsData.io API
  - Article Extractor and Summarizer API

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/DadvaiahPavan/NewsAI
cd NewsAI
```

2. Install dependencies:
```bash
cd project
npm install
```

3. Create a `.env` file in the project root and add your API keys:
```env
VITE_NEWS_API_KEY=your_newsdata_io_api_key
VITE_SUMMARY_API_KEY=your_summary_api_key
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

## 🔧 Configuration

The application can be configured through various environment variables:

- `VITE_NEWS_API_KEY`: Your NewsData.io API key
- `VITE_SUMMARY_API_KEY`: Your Article Summarizer API key

## 🌐 API Integration

### NewsData.io API
- Used for fetching real-time news articles
- Supports multiple languages and countries
- Provides category-based filtering

### Article Summarizer API
- Generates concise summaries of news articles
- Supports multiple languages
- Configurable summary length

## 🎨 UI Features

- Responsive design that works on all devices
- Dark mode support
- Smooth animations and transitions
- Category-based color coding
- Loading states and error handling
- Modern card-based article layout

## 🔍 Search Features

- Real-time search suggestions
- Advanced filtering options
- Support for multiple languages
- Category-specific search

## 📱 Mobile Support

The application is fully responsive and provides a seamless experience on:
- Desktop browsers
- Tablets
- Mobile devices

## 🛠️ Development

### Available Scripts

- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run preview`: Preview production build
- `npm run lint`: Run ESLint

### Project Structure

```
project/
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/        # Page components
│   ├── services/     # API and other services
│   ├── types/        # TypeScript type definitions
│   ├── config/       # Configuration files
│   └── utils/        # Utility functions
├── public/           # Static assets
└── dist/            # Production build
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## 🙏 Acknowledgments

- [NewsData.io](https://newsdata.io/) for providing the news API
- [RapidAPI](https://rapidapi.com/) for the article summarization API
- [Tailwind CSS](https://tailwindcss.com/) for the styling framework
- [React](https://reactjs.org/) for the frontend framework
- [Vite](https://vitejs.dev/) for the build tool
