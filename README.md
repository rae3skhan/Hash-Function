# Hash Function Demonstration

This project demonstrates the use of hash functions to ensure the integrity of messages during transmission. It simulates a scenario where a sender generates a hash of their message, sends the message and its hash to a receiver, and then the receiver verifies the message integrity by comparing the received hash with a hash generated from the received message. Additionally, it includes a "Man in the Middle" section to simulate an attacker modifying the message.

## Features

- **Generate Hash**: Allows the sender to generate a hash of their message using SHA-256.
- **Send Message**: Sends the message and its hash from the sender to the receiver.
- **Verify Hash**: Allows the receiver to verify the integrity of the received message by comparing the generated hash with the received hash.
- **Modify Message**: Simulates an attacker intercepting and modifying the message.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- CryptoJS

## Setup

To run this project, simply clone the repository, and open `index.html` in your browser.

```bash
git clone <repository-url>
cd <project-directory>
open index.html # On macOS
# or double-click index.html in your file explorer

```markdown
# Hash Function Demonstration

This project demonstrates the use of hash functions to ensure the integrity of messages during transmission. It simulates a scenario where a sender generates a hash of their message, sends the message and its hash to a receiver, and then the receiver verifies the message integrity by comparing the received hash with a hash generated from the received message. Additionally, it includes a "Man in the Middle" section to simulate an attacker modifying the message.

## Features

- **Generate Hash**: Allows the sender to generate a hash of their message using SHA-256.
- **Send Message**: Sends the message and its hash from the sender to the receiver.
- **Verify Hash**: Allows the receiver to verify the integrity of the received message by comparing the generated hash with the received hash.
- **Modify Message**: Simulates an attacker intercepting and modifying the message.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- CryptoJS

## Setup

To run this project, simply clone the repository, and open `index.html` in your browser.

```bash
git clone <repository-url>
cd <project-directory>
open index.html # On macOS
# or double-click index.html in your file explorer
```

## How It Works

1. **Sender**:
   - Enter your message in the textarea.
   - Click "Generate Hash" to generate a SHA-256 hash of your message.
   - Click "Send Message" to simulate sending the message and its hash to the receiver.

2. **Receiver**:
   - Upon "receiving" the message and its hash, click "Verify Hash" to check if the message's integrity is intact.
   - The verification result will be displayed below.

3. **Man in the Middle**:
   - To simulate an attack, modify the received message.
   - The receiver can then verify the hash again to see the integrity check fail.

 ## Author 
 Raees Khan  

## License

This project is open source and available under the [MIT License](LICENSE).
