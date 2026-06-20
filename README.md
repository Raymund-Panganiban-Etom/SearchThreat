# SearchThreat

A Windows Forms application designed to scan for security vulnerabilities.

## 📋 Prerequisites

Before building or running this project, ensure you have the following installed:

- **Visual Studio 2022** (Community, Professional, or Enterprise)
- **.NET Desktop Development** workload

## 🛠 Installation

### 1. Install Visual Studio
If you do not have Visual Studio installed, download it here:
[Download Visual Studio](https://visualstudio.microsoft.com/free-developer-offers/)

### 2. Configure Workloads
During installation (or via the Visual Studio Installer), ensure the following are selected:

- **Workload**: `.NET desktop development`
  - This includes the Windows Forms and .NET Framework tools required for this app.

- **Individual Components** (for a minimal setup):
  - `.NET 4.8 SDK` (or targeting pack)
  - `Windows 10/11 SDK`
  - `C# development tools`

## 🚀 How to Run

1. **Open the Solution**:
   - Launch Visual Studio.
   - Select **File > Open > Project/Solution**.
   - Navigate to the project directory and select `ThreatThreat.sln`.
   - *Alternatively*, double-click `ThreatScanner.csproj` to open it automatically.

2. **Restore Packages**:
   - If prompted, allow Visual Studio to restore NuGet packages.

3. **Set Startup Project**:
   - In the **Solution Explorer**, ensure the project named `ThreatScanner` is set as the **Startup Project**.

4. **Run the Application**:
   - Press **F5** or click the **Start Debugging** (green play button) in the toolbar.
   - The application entry point is located in `Program.cs`.

## 📂 Project Structure

- `ThreatScanner.sln`: Visual Studio solution file.
- `ThreatScanner.csproj`: Project configuration file.
- `Program.cs`: Application entry point.
- `Form1.cs` (or similar): Main Windows Forms interface.

## 📝 Notes

- This is a **.NET Framework (4.8)** Windows Forms application.
- Ensure your development machine has the necessary Windows SDKs installed to avoid build errors.

## 📄 License

[Add your license information here, e.g., MIT, Apache 2.0, or "Proprietary"]
