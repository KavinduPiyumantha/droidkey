# DroidKey Android Security Analysis Tool

DroidKey is a comprehensive tool for analyzing the security of Android APK files. It allows users to upload APK files and receive detailed security analysis results.

This project combines separate repositories for the backend and frontend:

- **Backend**: [https://anonymous.4open.science/r/DroidKey-Backend-A51A/](https://anonymous.4open.science/r/DroidKey-Backend-A51A/)
- **Frontend**: [https://anonymous.4open.science/r/DroidKey-Frontend-92C7/](https://anonymous.4open.science/r/DroidKey-Frontend-92C7/)

## Features

- **APK Upload and Analysis**: Automate security analysis of APK files.
- **Integration with MobSF**: Utilize Mobile Security Framework for in-depth analysis.
- **Decompilation with JADX**: Decompile APKs to Java source code for inspection.
- **Quark Engine Analysis**: Detect malware and malicious behaviors.
- **Detailed Reports**: Generate comprehensive security reports with recommendations.

## Installation & Usage

1. **Download the Repositories**:  
   Visit the following links to download the repositories as ZIP files:

   - DroidKey Backend: <a href="https://anonymous.4open.science/api/repo/DroidKey-Backend-A51A/zip" target="_blank">https://anonymous.4open.science/api/repo/DroidKey-Backend-A51A/zip</a>
   - DroidKey Frontend: <a href="https://anonymous.4open.science/api/repo/DroidKey-Frontend-92C7/zip" target="_blank">https://anonymous.4open.science/api/repo/DroidKey-Frontend-92C7/zip</a>

2. **Extract the ZIP Files**:  
   Extract both ZIP files into a single folder named `droidkey`. You should have two subfolders:

   - `droidkey-backend`
   - `droidkey-frontend`

3. **Start the Backend Server**:  
   Navigate to the backend folder and start the server:

   ```bash
   cd droidkey-backend
   python manage.py runserver 0.0.0.0:8001
   ```

4. **Run the Frontend Application**:  
   Navigate to the frontend folder and start the application:

   ```bash
   cd droidkey-frontend
   npm start
   ```

5. **Access the Application**:  
   Open [http://localhost:3000](http://localhost:3000) in your browser to use the application.

6. **Upload an APK File**:  
   Use the web interface to upload your APK file for analysis.

## Contributing

Contributions are welcome. Please submit pull requests to the respective repositories.

## License

This project is licensed under the MIT License.

---
