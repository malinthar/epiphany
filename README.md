# Generative AI Catalogue Site

Welcome to the Generative AI Catalogue Site! This website serves as a comprehensive resource for understanding the latest developments in generative artificial intelligence. Our goal is to simplify the overwhelming amount of information and buzzwords circulating in the GENAI community, making it accessible to everyone.

## Purpose

The Generative AI Catalogue Site is designed to gather and summarize key GENAI topics and buzzwords, providing users with a clear and concise overview of the current state of generative AI technologies. Whether you're curious about text-to-image models, large language models, or generative audio tools, this site aims to help you navigate the rapidly evolving landscape of generative artificial intelligence.

## Features

- **Dynamic Content**: The site utilizes Jekyll's data files and Markdown (.md) files to dynamically populate content related to various GENAI topics.
- **User-Friendly Navigation**: Easily browse through different sections to find information that interests you.
- **Consistent Layout**: The site maintains a consistent look and feel across all pages with a shared header and footer.
- **Markdown-Based Content**: All content is written in Markdown, making it easy to contribute and maintain.

## Content Structure

The site content is organized using Markdown files:

- **Topic Pages**: Each GENAI topic has its own .md file in the `_topics` directory
- **Model Descriptions**: Information about specific models in the `_models` directory
- **Tutorials**: Step-by-step guides in the `_tutorials` directory
- **News**: Updates on the latest GENAI developments in the `_posts` directory

## Styling with Markdown

The site uses custom styling defined in the front matter of Markdown files:

```yaml
---
layout: topic
title: Large Language Models
category: text
featured: true
image: /assets/images/llm-banner.jpg
---
```

## Getting Started

To set up the Generative AI Catalogue Site locally, follow these steps:

1. **Clone the Repository**:
   ```
   git clone https://github.com/yourusername/ai-catalogue-site.git
   cd ai-catalogue-site
   ```

2. **Install Jekyll**:
   Make sure you have Ruby and Bundler installed, then run:
   ```
   gem install jekyll bundler
   ```

3. **Install Dependencies**:
   ```
   bundle install
   ```

4. **Run the Site**:
   ```
   bundle exec jekyll serve
   ```
   Open your browser and go to `http://localhost:4000` to view the site.

## Contributing

We welcome contributions to improve the Generative AI Catalogue Site. If you have suggestions or would like to add new topics, please feel free to submit a pull request with your Markdown files.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any inquiries, please reach out to [your-email@example.com]. 

Thank you for visiting the Generative AI Catalogue Site! We hope you find it helpful in your exploration of generative artificial intelligence.