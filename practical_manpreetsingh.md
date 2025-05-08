# EXPERIMENT NO. 1
## Title: Android and iOS Development Environment
## Android Development Environment
### 1. Programming Languages
- **Java**: The traditional language used for Android development.
- **Kotlin**: A modern language recommended by Google for Android apps. It is concise and fully interoperable with Java.
### 2. Integrated Development Environment (IDE)
- **Android Studio**: The official IDE for Android development. It provides code editing, UI design, debugging, and device emulation.
### 3. Software Development Kit (SDK)
- **Android SDK**: A set of tools and libraries required to develop Android applications. It includes:
  - Android Emulator
  - Platform tools
  - Build tools
### 4. Build System
- **Gradle**: The build system used in Android Studio. It manages dependencies, builds APK files, and handles different versions of an app.
### 5. Emulator
- **Android Emulator**: A virtual device that lets developers test their apps without a physical phone.
### 6. User Interface Design
- **XML Layouts**: Used to define the structure of UI components.
- **Jetpack Compose**: A newer toolkit to design UI using Kotlin code in a declarative style.
### 7. Frameworks and Libraries
- **Android Jetpack**: A collection of libraries that help in building robust Android apps. Includes:
  - LiveData
  - ViewModel
  - Room (database)
  - Navigation
  - WorkManager
### 8. Testing
- **JUnit**: Used for unit testing the business logic.
- **Espresso**: Used for UI testing.
- **Robolectric**: Allows running unit tests on JVM without using an emulator.
## iOS Development Environment
### 1. Programming Languages
- **Objective-C**: A legacy programming language for iOS apps.
- **Swift**: A modern and safe programming language developed by Apple.

### 2. Integrated Development Environment (IDE)
- **Xcode**: The official IDE for iOS development. It includes a code editor, simulator, and Interface Builder.

### 3. Software Development Kit (SDK)
- **iOS SDK**: Includes essential libraries like:
  - UIKit (UI elements)
  - Foundation (data handling)
  - Core Data (database)

### 4. Build System
- **Xcode Build System**: Manages building, linking, and packaging of iOS apps.

### 5. Simulator
- **iOS Simulator**: Allows developers to test iOS apps on virtual iPhones, iPads, etc.

### 6. User Interface Design
- **Storyboard and XIB**: Visual tools in Xcode for designing user interfaces.
- **SwiftUI**: A modern framework for designing UI using Swift code.

### 7. Frameworks and Libraries
- **Cocoa Touch**: A base framework that includes UIKit, Foundation, and other core libraries.
- **Combine**: A framework to handle asynchronous tasks and event streams.

### 8. Testing
- **XCTest**: Used for both unit testing and UI testing in Xcode.
- **Quick/Nimble**: Popular third-party tools for writing readable tests.


<div style="page-break-after: always;"></div>

# EXPERIMENT NO. 2

## Title: Setting Up Android Studio and Understanding Its Basic Components

## 1. Installing Android Studio

### System Requirements

- **Windows**:
  - 64-bit Windows 8.1, 10, or later
  - Minimum 8 GB RAM (16 GB recommended)
  - 4 GB of available disk space minimum
- **macOS**:
  - macOS High Sierra (10.13) or newer
- **Linux**:
  - GNOME/KDE desktop environment
  - GNU C Library (glibc) 2.31 or later

### Steps to Download and Install

- Visit the [Android Studio download page](https://developer.android.com/studio).
- Click **Download Android Studio** and agree to the terms and conditions.

#### Installation Instructions

**On Windows:**
- Run the downloaded `.exe` file.
- Follow the Setup Wizard to install Android Studio, Android SDK, and emulator.

**On macOS:**
- Open the `.dmg` file.
- Drag and drop Android Studio into the **Applications** folder.
- Launch Android Studio and follow the configuration wizard.

**On Linux:**
- Extract the `.tar.gz` archive.
- Open a terminal, navigate to the extracted directory.
- Run the setup using `./studio.sh`.


## 2. Setting Up Android Studio

- **First Launch**: Open Android Studio and complete the initial setup wizard.
- **Install SDK Components**: The wizard installs the latest SDK version, platform tools, and build tools.
- **Emulator Setup**:
  - Use the **AVD Manager** to create virtual devices.
  - Configure device type, system image (API level), and resolution.


## 3. Basic Components of Android Studio

### 1. Welcome Screen
- **Quick Start Options**:
  - Start a new project
  - Open an existing project
  - Clone from GitHub or other version control
- **Recent Projects**: Access previous projects quickly.

### 2. Project Structure
- **Project View**:
  - Access Java/Kotlin files, resources, Gradle scripts, and manifests.
- **Android View**:
  - Filters project structure to only show relevant Android directories.

### 3. Editor Window
- Primary space to edit code.
- Tab-based interface to switch between files.
- **Split View** support for multitasking.

### 4. Tool Windows
- **Project**: Navigate files and directories.
- **Logcat**: View real-time logs and debugging output.
- **Build**: Monitor build process and errors.
- **Terminal**: Run shell commands directly.
- **Event Log**: Shows background operations like Gradle syncs.

### 5. Toolbar
- **Run/Debug Buttons**: Launch or debug apps on emulator/device.
- **AVD Manager**: Create or manage virtual devices.
- **SDK Manager**: Install or update Android SDK components.

### 6. Code Editor
- **Syntax Highlighting**: Enhances code readability.
- **Code Completion**: Suggests classes, methods, variables.
- **Linting**: Highlights potential issues in real-time.
- **Refactoring Tools**: Rename, extract, or move code safely.

### 7. Layout Editor
- **Design View**: Drag-and-drop UI builder.
- **Code/Text View**: XML code editing mode.
- **Palette**: Collection of UI components (TextView, Button, etc.).
- **Component Tree**: Displays layout hierarchy.


## 4. Creating a Simple Android Project

### Steps to Start a New Project
1. Open Android Studio and select **"Start a new Android Studio project"**.
2. Choose a template (e.g., **Empty Activity**).
3. Fill in project details:
   - Name
   - Package name
   - Save location
   - Language: Java or Kotlin
   - Minimum SDK version

### Exploring the Project Structure
- **`app/java`**: Contains your Java/Kotlin source files.
- **`app/res`**: Contains XML layouts, images, and other resources.
- **`AndroidManifest.xml`**: Declares components and permissions.

### Running the App
- Click the green **Run** button.
- Select a connected device or virtual emulator.
- App will compile, install, and launch.

## 5. Understanding Android App Components
### 1. Activities
- Represent a single screen with a user interface.
- Extend `Activity` or `AppCompatActivity`.

### 2. Layouts
- XML files that define the UI structure.
- Located in `res/layout`.

### 3. Resources
- Include strings (`strings.xml`), colors (`colors.xml`), styles (`styles.xml`), and drawable assets.
- Allow easier localization and design consistency.

### 4. Manifests
- The `AndroidManifest.xml` file contains:
  - App name and icon
  - Activities, services, broadcast receivers
  - Permissions (e.g., Internet, camera)

### 5. Gradle Scripts
- Used for build configuration and dependencies.
- `build.gradle (Project)`: Configuration for all modules.
- `build.gradle (Module: app)`: App-specific dependencies and settings.

## Additional Features that u can add

- **Plugins**: Enhance functionality (e.g., Git, Firebase, Material UI plugins).
- **Version Control Integration**: Supports Git, GitHub, Bitbucket natively.
- **Real-Time Preview**: Layout preview updates as you write XML.
- **Live Templates**: Use shortcuts like `sout`, `Toast`, etc., for rapid coding.

<div style="page-break-after: always;"></div>



# EXPERIMENT NO. 3

## Title: Android User Interface Design – Studying XML Files Required for UI Design


## 1. `AndroidManifest.xml`

This is one of the most critical files in an Android project. It provides essential information about your app to the Android system, which the system must have before it can run any of the app's code.

### **Key Responsibilities:**
- Declares activities, services, broadcast receivers, and content providers.
- Specifies required permissions (e.g., internet access).
- Declares the minimum and target SDK versions.
- Sets the launcher activity.
- Registers app-wide themes, icons, and more.

### **Example:**
```xml
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.myapp">

    <uses-permission android:name="android.permission.INTERNET" />

    <application
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:theme="@style/AppTheme">

        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />
                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>

    </application>
</manifest>
```

---

## 2. `activity_main.xml`

This is the layout file that defines the user interface for an Activity — typically the main screen.

### **Key Elements:**
- Defines the structure of UI using containers like `ConstraintLayout`, `LinearLayout`, etc.
- Includes UI widgets like `TextView`, `Button`, `EditText`, etc.
- Uses layout attributes to define position and size.

### **Example:**
```xml
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/welcome_message"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/button_text"
        app:layout_constraintTop_toBottomOf="@id/textView"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

---

## 3. `colors.xml`

This file defines color resources used in the app. Defining colors centrally ensures consistency and simplifies theme changes across the app.

### **Use Cases:**
- Primary and secondary theme colors
- Background, text, accent colors

### **Example:**
```xml
<resources>
    <color name="colorPrimary">#6200EE</color>
    <color name="colorPrimaryDark">#3700B3</color>
    <color name="colorAccent">#03DAC5</color>
    <color name="white">#FFFFFF</color>
    <color name="black">#000000</color>
</resources>
```

---

## 4. `strings.xml`

Contains all string resources used in the app, which allows for easier localization and maintenance.

### **Benefits:**
- Avoids hardcoding strings in the code
- Facilitates translation for multiple languages

### **Example:**
```xml
<resources>
    <string name="app_name">MyApp</string>
    <string name="welcome_message">Welcome to MyApp!</string>
    <string name="button_text">Click Me</string>
</resources>
```

---

## 5. `styles.xml`

This file allows you to define reusable visual properties (fonts, sizes, colors) for UI components.

### **Purpose:**
- Centralized styling for consistency
- Enables theming across widgets like buttons, text, and layouts

### **Example:**
```xml
<resources>
    <!-- Base application theme -->
    <style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar">
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">@color/colorAccent</item>
    </style>

    <!-- Custom button style -->
    <style name="CustomButton">
        <item name="android:background">@color/colorAccent</item>
        <item name="android:textColor">@android:color/white</item>
        <item name="android:padding">12dp</item>
    </style>
</resources>
```

---

## 6. `themes.xml`

Defines the application-wide theme that can be applied to all activities or individually. It's more modern and modular than `styles.xml`.

### **Features:**
- Supports Material Design theming
- Defines colors, fonts, shapes, elevation, etc.

### **Example:**
```xml
<resources xmlns:tools="http://schemas.android.com/tools">
    <!-- Base application theme -->
    <style name="Theme.MyApp" parent="Theme.MaterialComponents.DayNight.DarkActionBar">
        <!-- Primary brand color -->
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryVariant">@color/colorPrimaryDark</item>
        <item name="colorOnPrimary">@android:color/white</item>

        <!-- Secondary brand color -->
        <item name="colorSecondary">@color/colorAccent</item>
        <item name="colorOnSecondary">@android:color/black</item>
    </style>
</resources>


<div style="page-break-after: always;"></div>


# EXPERIMENT NO 4: Android User Interface Design  
**Objective:** To implement different types of layouts like Linear, Relative, Grid, and Table.

## 1. Linear Layout Example

Linear Layout arranges elements in a single direction - either horizontally or vertically.

```xml
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Linear Layout Example" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Click Me" />
</LinearLayout>
```

## 2. Relative Layout Example

Relative Layout positions elements in relation to parent or other elements.

```xml
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="16dp">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Relative Layout Example" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/textView"
        android:text="Click Me" />
</RelativeLayout>
```

## 3. Grid Layout Example

Grid Layout arranges elements in a grid of rows and columns.

```xml
<GridLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:columnCount="2"
    android:padding="16dp">

    <Button
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_columnWeight="1"
        android:text="Button 1" />

    <Button
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_columnWeight="1"
        android:text="Button 2" />
</GridLayout>
```

## 4. Table Layout Example

Table Layout organizes elements into rows and columns like an HTML table.

```xml
<TableLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:stretchColumns="*"
    android:padding="16dp">

    <TableRow>
        <TextView
            android:text="Username" />
        <EditText
            android:hint="Enter username" />
    </TableRow>

    <TableRow>
        <TextView
            android:text="Password" />
        <EditText
            android:hint="Enter password"
            android:inputType="textPassword" />
    </TableRow>
</TableLayout>
```

## 5. Practical Example: Registration Form

This example demonstrates a complete registration form using nested LinearLayouts.

```xml
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="16dp"
    tools:context=".RegistrationActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <!-- Form Title -->
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Registration Form"
            android:textSize="24sp"
            android:textStyle="bold"
            android:gravity="center"
            android:layout_marginBottom="8dp"/>

        <!-- Form Description -->
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Fill out the form carefully for registration"
            android:textSize="14sp"
            android:gravity="center"
            android:layout_marginBottom="24dp"/>

        <!-- Student Name Field -->
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Student Name"
            android:textSize="16sp"
            android:layout_marginBottom="8dp"/>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:layout_marginBottom="16dp">

            <EditText
                android:id="@+id/editTextFirstName"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:hint="First Name"
                android:padding="12dp"
                android:background="@drawable/edit_text_border"
                android:layout_marginEnd="8dp"
                android:inputType="textPersonName"/>

            <EditText
                android:id="@+id/editTextLastName"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:hint="@string/last_name"
                android:padding="12dp"
                android:background="@drawable/edit_text_border"
                android:inputType="textPersonName"/>
        </LinearLayout>

        <!-- Gender and Email Fields -->
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:layout_marginBottom="16dp">

            <LinearLayout
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:orientation="vertical"
                android:layout_marginEnd="8dp">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="@string/gender"
                    android:textSize="16sp"
                    android:layout_marginBottom="8dp"/>

                <Spinner
                    android:id="@+id/spinnerGender"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="12dp"
                    android:background="@drawable/spinner_border"/>
            </LinearLayout>

            <LinearLayout
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:orientation="vertical">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="@string/student_e_mail"
                    android:textSize="16sp"
                    android:layout_marginBottom="8dp"/>

                <EditText
                    android:id="@+id/editTextEmail"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:hint="@string/ex_myname_example_com"
                    android:padding="12dp"
                    android:background="@drawable/edit_text_border"
                    android:inputType="textEmailAddress"/>
            </LinearLayout>
        </LinearLayout>

        <!-- Student ID and Classes Fields -->
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:layout_marginBottom="24dp">

            <LinearLayout
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:orientation="vertical"
                android:layout_marginEnd="8dp">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="@string/student_id"
                    android:textSize="16sp"
                    android:layout_marginBottom="8dp"/>

                <EditText
                    android:id="@+id/editTextStudentId"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="12dp"
                    android:background="@drawable/edit_text_border"
                    android:inputType="text"/>
            </LinearLayout>

            <LinearLayout
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:orientation="vertical">

                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="@string/list_of_classes"
                    android:textSize="16sp"
                    android:layout_marginBottom="8dp"/>

                <Spinner
                    android:id="@+id/spinnerClasses"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:padding="12dp"
                    android:background="@drawable/spinner_border"/>
            </LinearLayout>
        </LinearLayout>

        <!-- Submit Button -->
        <Button
            android:id="@+id/buttonSubmit"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Submit"
            android:textColor="#FFFFFF"
            android:backgroundTint="#4CAF50"
            android:padding="12dp"
            tools:ignore="HardcodedText" />

    </LinearLayout>
</ScrollView>
```
![Signup Page Screenshot](s1.png)

## 6. Advanced Example: Calculator UI with ConstraintLayout and GridLayout

This example shows how to create a calculator interface using a combination of ConstraintLayout and GridLayout.

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <!-- Display Screen -->
    <TextView
        android:id="@+id/tvDisplay"
        android:layout_width="0dp"
        android:layout_height="120dp"
        android:background="#FFFFFF"
        android:text=""
        android:textSize="32sp"
        android:gravity="end|center_vertical"
        android:padding="16dp"
        android:textColor="#000000"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <!-- First Row Buttons: AC, (, ), % -->
    <GridLayout
        android:id="@+id/row1"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:columnCount="4"
        android:rowCount="1"
        app:layout_constraintTop_toBottomOf="@+id/tvDisplay"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintWidth_percent="0.9">

        <Button
            android:text="AC"
            android:layout_width="0dp"
            android:layout_height="80dp"
            android:layout_columnWeight="1"
            android:background="#6E7581"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />

        <Button
            android:text="("
            android:layout_width="0dp"
            android:layout_height="80dp"
            android:layout_columnWeight="1"
            android:background="#6E7581"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />

        <Button
            android:text=")"
            android:layout_width="0dp"
            android:layout_height="80dp"
            android:layout_columnWeight="1"
            android:background="#6E7581"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />

        <Button
            android:text="%"
            android:layout_width="0dp"
            android:layout_height="80dp"
            android:layout_columnWeight="1"
            android:background="#6E7581"
            android:textColor="#FFFFFF"
            android:textSize="24sp" />
    </GridLayout>

    <!-- Numeric Buttons and Operators -->
    <GridLayout
        android:id="@+id/numericGrid"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="16dp"
        android:columnCount="4"
        android:rowCount="5"
        app:layout_constraintTop_toBottomOf="@+id/row1"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintWidth_percent="0.9">

        <!-- Row 1: 7, 8, 9, / -->
        <Button android:text="7" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="8" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="9" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="/" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#6E7581" android:textColor="#FFFFFF" android:textSize="24sp"/>

        <!-- Row 2: 4, 5, 6, * -->
        <Button android:text="4" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="5" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="6" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="*" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#6E7581" android:textColor="#FFFFFF" android:textSize="24sp"/>

        <!-- Row 3: 1, 2, 3, - -->
        <Button android:text="1" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="2" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="3" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="-" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#6E7581" android:textColor="#FFFFFF" android:textSize="24sp"/>

        <!-- Row 4: ., 0, =, + -->
        <Button android:text="." android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="0" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#E3F2FD" android:textColor="#000000" android:textSize="24sp"/>
        <Button android:text="=" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#F66335" android:textColor="#FFFFFF" android:textSize="24sp"/>
        <Button android:text="+" android:layout_width="0dp" android:layout_height="80dp" android:layout_columnWeight="1" android:background="#6E7581" android:textColor="#FFFFFF" android:textSize="24sp"/>
    </GridLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
```
![Signup Page Screenshot](s2.png)
## Key Layout Concepts

### Linear Layout
- Arranges elements in a single line (horizontal or vertical)
- Uses `android:orientation="vertical"` or `android:orientation="horizontal"`
- Weight attribute (`android:layout_weight`) distributes space proportionally

### Relative Layout
- Positions elements relative to parent or sibling elements
- Common attributes: `android:layout_below`, `android:layout_toRightOf`, `android:layout_alignParentTop`

### Grid Layout
- Organizes content in a grid of rows and columns
- Use `android:rowCount` and `android:columnCount` to define grid size
- `android:layout_columnWeight` distributes column space

### Table Layout
- Similar to HTML tables
- Contains `<TableRow>` elements
- `android:stretchColumns="*"` makes all columns expandable

### ConstraintLayout
- Flexible positioning with constraints to other views or parent
- Reduces nested layouts for better performance
- Uses constraints like `app:layout_constraintTop_toBottomOf`

### Practical Tips
- Use ScrollView for forms that might extend beyond screen
- Nest layouts strategically for complex UIs
- Use weight attributes for proportional sizing
- ConstraintLayout reduces layout nesting and improves performance



# Extended Android UI Layout using ConstraintLayout

This layout extends the previous survey form by adding:

- A `CheckBox` for expressing preference
- A `ChipGroup` for feature rating
- A new question for recommendation

## XML Code Snippet (continued `activity_main.xml`)

```xml
<!-- Question 1 TextView -->
<TextView
    android:id="@+id/textViewQuestion1"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:text="Do you like our app?"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/textViewTitle"
    android:layout_marginTop="16dp"
    android:layout_marginBottom="8dp" />

<!-- CheckBox for like option -->
<CheckBox
    android:id="@+id/checkBox"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="I like it"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/textViewQuestion1"
    android:layout_marginBottom="16dp" />

<!-- Question 2 TextView -->
<TextView
    android:id="@+id/textViewQuestion2"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:text="Rate the app features:"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/checkBox"
    android:layout_marginTop="16dp"
    android:layout_marginBottom="8dp" />

<!-- ChipGroup for features -->
<com.google.android.material.chip.ChipGroup
    android:id="@+id/chipGroup"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/textViewQuestion2"
    android:layout_marginBottom="16dp"
    android:orientation="horizontal">

    <com.google.android.material.chip.Chip
        android:id="@+id/chip1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Feature 1" />

    <com.google.android.material.chip.Chip
        android:id="@+id/chip2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Feature 2" />

    <com.google.android.material.chip.Chip
        android:id="@+id/chip3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Feature 3" />
</com.google.android.material.chip.ChipGroup>

<!-- Question 3 TextView -->
<TextView
    android:id="@+id/textViewQuestion3"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:text="Would you recommend our app?"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/chipGroup"
    android:layout_marginTop="16dp"
    android:layout_marginBottom="8dp" />
# Final Part of UI Layout – activity_main.xml

This section completes the UI with controls for submitting the form and interacting through toggles and icons.

## XML Code Snippet (continued)

```xml
<!-- Question 3 TextView -->
<TextView
    android:id="@+id/textViewQuestion3"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:text="Would you recommend our app?"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/chipGroup"
    android:layout_marginTop="16dp"
    android:layout_marginBottom="8dp" />

<!-- RadioGroup for recommendations -->
<RadioGroup
    android:id="@+id/radioGroup"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/textViewQuestion3"
    android:layout_marginBottom="16dp" />

<!-- ToggleButton for notifications -->
<ToggleButton
    android:id="@+id/toggleButton"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:textOff="Enable Notifications"
    android:textOn="Disable Notifications"
    android:layout_marginTop="112dp"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/radioGroup"
    app:layout_constraintHorizontal_bias="0.0" />

<!-- Submit Button -->
<Button
    android:id="@+id/button"
    android:layout_width="0dp"
    android:layout_height="wrap_content"
    android:text="Submit"
    android:layout_marginTop="28dp"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/toggleButton"
    app:layout_constraintHorizontal_bias="0.0" />

<!-- ImageButton for camera -->
<ImageButton
    android:id="@+id/imageButton"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:src="@android:drawable/ic_menu_camera"
    android:layout_marginTop="32dp"
    app:layout_constraintTop_toBottomOf="@id/button"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.473" />

<!-- FloatingActionButton -->
<com.google.android.material.floatingactionbutton.FloatingActionButton
    android:id="@+id/fab"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:src="@android:drawable/ic_dialog_email"
    android:layout_marginTop="16dp"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.473" />


# Final UI Elements – activity_main.xml

This section adds individual `RadioButton` choices and completes the layout.


```xml
<!-- Additional layout constraint (if required) -->
app:layout_constraintTop_toBottomOf="@id/imageButton"
app:layout_constraintVertical_bias="0.0" />

<!-- RadioButton - Yes -->
<RadioButton
    android:id="@+id/radioButton1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Yes"
    tools:layout_editor_absoluteX="21dp"
    tools:layout_editor_absoluteY="279dp" />

<!-- RadioButton - No -->
<RadioButton
    android:id="@+id/radioButton2"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="No"
    tools:layout_editor_absoluteX="123dp"
    tools:layout_editor_absoluteY="282dp" />

</androidx.constraintlayout.widget.ConstraintLayout>
