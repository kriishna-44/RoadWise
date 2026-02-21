<<<<<<< HEAD
<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# ROADWISE 🎯

## Basic Details

### Team Name: Error 404!

### Team Members
- Member 1: Safeena K S - MUTHOOT INSTITUTE OF TECHNOLOGY & SCIENCE
- Member 2: Krishna Krishnakumar - MUTHOOT INSTITUTE OF TECHNOLOGY & SCIENCE

### Hosted Project Link
https://road-wise-five.vercel.app/

### Project Description
RoadWise is an interactive web-based road safety simulation designed to educate users about real-life traffic scenarios and safe driving practices. The platform creates a virtual driving environment where users can experience common road situations and learn how to respond correctly.

### The Problem statement
Road accidents are a leading cause of injuries and fatalities, often due to lack of driver awareness and poor understanding of traffic rules. Traditional road safety education is limited and theoretical, failing to provide real-world practice. There is a need for an interactive, engaging solution that helps users learn safe driving through realistic scenarios.

### The Solution
RoadWise provides an interactive, web-based driving simulator where users experience realistic traffic scenarios. It teaches safe driving by simulating lanes, signals, pedestrian crossings, and unexpected events. Users get instant feedback on their actions, helping them learn traffic rules, improve decision-making, and prevent accidents in a fun, practical way.

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: JavaScript, HTML, CSS
- Frameworks used: None (vanilla JS)
- Libraries used: localStorage API for saving selections
- Tools used: VS Code, Git, Chrome DevTools



---

## Features

Vehicle selection (car/bike)
Lane and road traffic simulation
Traffic signals with violation detection (red/green)
Pedestrian crossings and zebra crossings
Collision detection and real-time warnings
Score tracking for gamified learning
Neon-themed interactive UI

### For Software:

## Implementation
Installation
# Clone the repository
git clone https://github.com/kriishna-44/RoadWise.git
# Open index.html in a browser to start
Run

Simply open index.html in any modern browser (Chrome, Edge, Firefox).
No server setup required as the game is fully front-end.


## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![Screenshot1]
<img width="1321" height="778" alt="Screenshot 2026-02-21 090113" src="https://github.com/user-attachments/assets/c19ebfb0-8dde-456a-a142-e836430b357d" />
{ Entering page where you can select a vehicle {car/bike} that you want to drive/ride. then Click on 'START GAME' to play the game. }

![Screenshot2]
<img width="1919" height="903" alt="Screenshot 2026-02-21 090210" src="https://github.com/user-attachments/assets/e1260a9c-0f42-4efd-9648-4712e26cb3b4" />

{ interface when you select 'Car', whenever you're making a mistake in driving, it will raise an warning message until you correct your mistake }

![Screenshot3]
<img width="1915" height="894" alt="Screenshot 2026-02-21 090409" src="https://github.com/user-attachments/assets/70f701c3-80f2-4c75-a351-c49c9022aa00" />
{ interface when you select 'Bike', whenever you're making a mistake in riding, it will raise an warning message  }

some of the warning messages in both car and bike :
- stop for pedestrian
- vehicle collision
- changing lane
- red traffic signal etc...

#### Diagrams

**System Architecture:**

User interacts with browser → JS logic handles controls, vehicle movement, collisions → localStorage saves selection → Game updates in real-time with requestAnimationFrame.

**Application Workflow:**

![Workflow](docs/workflow.png)

Select vehicle → 2. Start game → 3. Navigate lanes & avoid collisions → 4. Score updates → 5. Receive warnings for violations


## Additional Documentation
https://drive.google.com/file/d/1GLMkD86VaP7nE3ZgRLm1QfyW3xgwvlPH/view?usp=drive_link


#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
=======
# RoadWise
RoadWise is an interactive road safety simulator that teaches users safe driving practices through realistic traffic scenarios. With lanes, signals, pedestrians, and unexpected events, users get instant feedback on their decisions, promoting awareness, responsible driving, and accident prevention in a fun, engaging way.
>>>>>>> ae4bbfdbaccceae287c86d6b4ccd361fde4746ea


