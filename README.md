# 📸 GitHub CDN for Images Using Gaac

Welcome to the **GitHub CDN for Images** repository! This repository is used to store and serve images via GitHub using the third-party tool [Gaac](https://gaac.vercel.app). Gaac provides a simple way to turn your GitHub repositories into a CDN for your static assets.

## 📦 Repository Setup

### 1. **Create a GitHub Repository**

1. Go to [GitHub](https://github.com) and create a new repository where you will store your images.

2. Clone the repository to your local machine and add your images to this repository.

3. Push the changes to GitHub.

   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   # Add images
   git add .
   git commit -m "Add initial set of images"
   git push origin main
   ```

### 2. **Connect GitHub with Gaac**

1. Visit [Gaac](https://gaac.vercel.app).

2. **Connect Your GitHub Account**: Follow the instructions to authenticate and connect your GitHub account with Gaac.

3. **Select Your Repository**: Choose the repository you created for storing your images.

4. **Upload Images**: After connecting, you can start uploading images directly through the Gaac interface. 

5. **Get CDN URLs**: Once uploaded, Gaac will provide you with CDN URLs for each image. You can use these URLs to embed images in your projects.

## 📂 Usage

After uploading images via Gaac, you will receive a CDN URL for each image. You can use these URLs to serve images efficiently in your web applications or any other projects.

### Example

Here’s an example of how to use a CDN URL in an HTML file:

```html
<img src="https://your-cdn-url.com/path/to/image.jpg" alt="Description of Image" />
```

## 🚀 Features

- **Free Hosting**: Use GitHub’s infrastructure to host your images at no cost.
- **Easy Integration**: Connect your GitHub repository with Gaac for seamless image management.
- **High Performance**: Leverage CDN URLs for fast and reliable image delivery.

## 📋 Contributing

If you have suggestions or improvements for this setup, feel free to fork the repository and submit a pull request. You can also open an issue if you encounter any problems or have questions.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

