import qrcode
from PIL import Image  # Pillow is needed to display the image

# Create QR code
qr = qrcode.make("https://www.Example website")

# Show the QR code
qr.show()  # This opens the image in your default image viewer




