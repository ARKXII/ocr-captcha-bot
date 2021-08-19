# ocr-captcha-bot
A project to deploy a OCR bot to read captchas in a website then input the results somewhere.
Project will be written and deployed in Python.

### Project Structure
- **Image Capturing Module**
  - Captures a part of the screen.
  - This module only captures a specific part of the screen, requiring the user to not move any windows.

- **Image Interpretation Module**
  - Takes the screenshot and interprets the captcha.

- **Website Automation Module**
  - Inputs the interpreted data into the website textbox and navigates to the next page.
  - *This requires further research.*
