# Qr Code Genarator
This is a simple, fully self-contained QR code generator built with HTML, CSS, and JavaScript.
You can use it offline, no installation or server required. Just open the file in your browser.
What this tool does
It lets you create different kinds of QR codes in seconds and download them as PNG images.
Supported QR types:

Plain text or any URL
Email (with recipient, subject, and body)
Contact (basic vCard with name, phone, email)
Calendar event (title, start time, end time, location)
Geo location (latitude, longitude, optional label)
Wi-Fi network (SSID + password)
Phone number (opens dialer)
SMS (phone number + pre-filled message)

Main features

Clean modern design with light and dark mode
Responsive layout (works well on mobile and desktop)
Choose QR size: small (180 px), medium (260 px), large (380 px)
Custom filename for downloaded images
One-click copy QR code to clipboard (modern browsers)
Instant preview after generation
No data leaves your device everything runs locally

How to open and use it

Save the code as a file named qr-generator.html (or any name ending with .html)
Double-click the file or drag it into your browser (Chrome, Firefox, Edge, Safari, etc.)
The page opens immediately no need for internet after the first load
Select the type of QR code from the dropdown menu
Fill in the fields that appear (required fields are shown)
Choose your preferred QR size from the dropdown
(Optional) Enter a custom filename
Click "Generate QR"
The QR code appears on the right
Use "Copy to Clipboard" or "Download PNG" buttons below the preview

You can now scan the QR code with your phone camera or any QR reader to test it.
Detailed explanation of each section
Content type dropdown
Select what kind of QR you want to create. Changing this shows/hides the relevant input fields.
# Text / URL
Enter any text or link. This is the most flexible option  use it for websites, social profiles, payment links, notes, etc.
# Email
Fill in recipient email, subject, and message body. Scanning opens the email app with everything pre-filled.
# Contact (vCard)
Enter name, phone, and email. Scanning adds the contact directly to the phone's address book (most phones support this).
# Calendar Event
Set event title, start/end time (use the date time picker), and optional location. Scanning adds the event to the calendar app.
# Geo Location
Enter latitude and longitude (decimal format), plus optional label. Scanning opens maps at that exact spot.
# Wi-Fi
Enter network name (SSID) and password. Scanning connects the phone to the Wi-Fi without typing anything.
# Phone
Enter a phone number. Scanning opens the dialer with the number ready to call.
# SMS
Enter phone number and optional message. Scanning opens the messaging app with text pre-filled.
# QR Size selector
Choose how big the QR code should be. Larger sizes are easier to scan from a distance but take more space.
# Filename input
Type the name you want for the downloaded file (without .png). The tool automatically cleans invalid characters.
# Generate QR button
Creates the QR code using your inputs and shows it in the preview area.
# Copy to Clipboard button
Copies the QR image to your clipboard so you can paste it into messages, documents, or design tools.
# Download PNG button
Saves the QR code as a PNG file using the filename you chose.
# Preview area
Shows the generated QR code. You can right-click → save image manually if needed.
# Dark mode toggle
Switches between light and dark theme. Your preference is saved so it stays the same next time you open the file.
