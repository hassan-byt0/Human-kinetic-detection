# Human-kinetic-detection

This repository contains a Streamlit application developed for the research journal **"Photo-Assisted Piezoelectric Energy Harvesters and Sensors Using PVDF Matrix Stabilized α-FAPbI3 Perovskite with AI/ML Human Kinematic Detection."**


![Interface](https://drive.google.com/uc?id=1HJiFmMsGZr7TtPX51Sv6PVt9lkyqwUgs "Screenshot of the app")
![Interface](https://drive.google.com/uc?id=1AUxBsD87vtTT_tTnVT_OPZXtZbRULGEo "Screenshot of the app")

Follow the instructions below to set up and run the application.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
- Python 3.7 or higher
- pip (Python package manager)
- npm (Node.js package manager)

### Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/hassan-byt0/Human-kinetic-detection.git

2. Navigate to the `app` directory:
   ```bash
   cd Human-kinetic-detection/app
   ```

3. Install Streamlit with the `-q` tag:
   ```bash
   pip install streamlit -q
   ```

4. Verify the content of the directory:
   ```bash
   ls
   ```

5. Obtain the public IP for tunneling (required only once per execution):
   ```bash
   wget -q -O - ipv4.icanhazip.com
   ```

### Running the Application

Run the Streamlit application and expose it via localtunnel:
   ```bash
   streamlit run app.py & npx localtunnel --port 8501
   ```

After executing the above command, you will see a URL generated by `localtunnel`. Use this URL to access the application interface.

---

### Notes

- The IP address from step 5 is required only the first time you execute the application.
- Ensure you select `your_url` from the generated `localtunnel` URL for interfacing with the app.

---

### Results:

## Contributing

Contributions are welcome! Please create a pull request for any changes or improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
