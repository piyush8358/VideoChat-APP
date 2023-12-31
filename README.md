# VideoChat-APP


# Output

https://github.com/piyush8358/VideoChat-APP/assets/96904569/75373775-bc27-4b83-b303-7cd0649d2012

---

# Voice Chat Application using Python, OpenCV, and Sockets

This is a simple voice chat application that allows you to send and receive live video streams between a client and server using Python, OpenCV, and sockets. The client captures video from your webcam and sends it to the server, which displays the video in real-time.

## Prerequisites

- Python 3.x
- OpenCV (`opencv-python` package)
- A webcam for capturing video

## Usage

1. Clone or download this repository to your local machine.

2. Install the required Python packages if you haven't already:

   ```bash
   pip install opencv-python
   ```

3. Run the server.py script on one computer:

   ```bash
   python server.py
   ```

4. Run the client.py script on another computer:

   ```bash
   python client.py
   ```

5. The client will connect to the server, and you will see your webcam video displayed on both the client and server sides. Press 'q' on either the client or server side to exit the application.

## Configuration

- **IP Address and Port**: By default, the server binds to all available network interfaces ('') and uses port 9999. You can modify the IP address and port in both client.py and server.py files to match your network configuration.

## Troubleshooting

- If you encounter any issues, make sure that you have installed the required packages and that your webcam is accessible and working correctly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This code is for educational purposes and can serve as a starting point for building more advanced video chat applications.

---