# Content-Fulfill

**Content-Fulfill** is an AI-powered content creation assistant built with **Ruby on Rails**. It helps creators generate high-quality content by providing minimal input and guiding them through every step of the content development process — from ideation to publishing.

---

## 🚀 Features

- 🤖 **AI-Driven Content Generation**  
  Automatically creates articles, blog posts, and marketing content with just a prompt.

- ✍️ **Guided Content Development**  
  Structured workflow from ideation to final editing, optimized for creators.

- 📌 **Prompt-Based Workflows**  
  Generate drafts based on short descriptions or keywords.

- 🧠 **Content Optimization Tools**  
  Tone adjustment, grammar enhancement, keyword inclusion, and SEO tips.

- 🛠️ **Customizable Templates**  
  Ready-to-use formats for blogs, emails, social media, and product pages.

- 🔐 **User Authentication**  
  Secure login system and private content management.

---

## 🧱 Tech Stack

- **Backend**: Ruby on Rails 7+
- **Frontend**: ERB + Hotwire (Turbo + Stimulus)
- **Database**: PostgreSQL
- **AI Integration**: OpenAI / GPT-based API
- **Authentication**: Devise
- **Background Jobs**: Sidekiq
- **Deployment**: Heroku / Render / Docker

---

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/content-fulfill.git
   cd content-fulfill
   ```

2. **Install dependencies**:

   ```bash
   bundle install
   yarn install # if using jsbundling-rails or webpacker
   ```

3. **Set up the database**:

   ```bash
   rails db:create db:migrate
   ```

4. **Configure environment variables**:
   Create a `.env` file or add to `credentials.yml.enc`:

   ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   ```

5. **Start the Rails server**:

   ```bash
   rails server
   ```

---

## 🧪 Running Tests

Run test suite using:

```bash
bundle exec rspec
```

or

```bash
rails test
```

---

## 🗺️ Roadmap

* [ ] Multilingual content generation
* [ ] Team collaboration features
* [ ] CMS integrations (WordPress, Ghost, etc.)
* [ ] Custom prompt builder
* [ ] Real-time AI editing assistant

---

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 📬 Contact

For support or feature requests, open an issue or contact [megha.koshti@outlook.com](mailto:megha.koshti@outlook.com]).

---

**Empower your creativity — let Content-Fulfill handle the heavy lifting.**
