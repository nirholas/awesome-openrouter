# Contributing

Want to add your app to the "Works with OpenRouter" list? Follow these steps!

**This directory is published at [openrouter.ai/awesome](https://openrouter.ai/awesome)** — your submission gets a real backlink from a high-traffic AI site. Great for SEO and discoverability.

## Requirements

Your app must:
- Use [OpenRouter](https://openrouter.ai) for AI model access
- Allow users to bring their own OpenRouter API Key
- Be publicly accessible (or have a public landing page)
- Have a logo image

## How to Submit

1. **Fork this repository**

2. **Create a folder for your app** in the `apps/` directory:
   ```
   apps/your-app-name/
   ├── app.yaml
   └── logo.png
   ```

   Use lowercase letters, numbers, and hyphens for the folder name (e.g., `my-cool-app`).

3. **Create your `app.yaml` file** with the following format:

   ```yaml
   name: "Your App Name"
   description: "A brief description of your app (1-2 sentences, max 300 characters)"
   url: "https://your-app-url.com"
   docs: "https://your-app-url.com/docs/openrouter"  # Link to OpenRouter setup instructions
   tags:
     - chat  # Choose from: chat, coding, productivity, creative, research, other
   open_source: "https://github.com/you/your-app"  # Optional: remove if not open source
   date_added: "2025-01-08"  # Use today's date in YYYY-MM-DD format
   ```

4. **Add your logo**
   - File must be named `logo.png`
   - Recommended size: 128x128 or 256x256 pixels
   - Square aspect ratio
   - PNG format

5. **Submit a Pull Request**
   - PRs are validated automatically
   - **Do not edit README.md** — it's auto-generated after merge
   - Once approved and merged, a GitHub Action will regenerate the README to include your app

## Valid Tags

Choose one or more tags that describe your app:

| Tag | Description |
|-----|-------------|
| `chat` | Conversational AI, chatbots, assistants |
| `coding` | Development tools, code generation, IDEs |
| `productivity` | Task management, automation, workflows |
| `creative` | Art, writing, music, content creation |
| `research` | Analysis, search, knowledge management |
| `other` | Anything that doesn't fit the above |

## Example

See [`apps/kilocode/`](apps/kilocode/) for a complete example.

## Questions?

Open an issue if you have questions or need help with your submission.
