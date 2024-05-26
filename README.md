# SwiftUI Dashboard Task

## Introduction
Hello, my name is Varshitha Y S. I am eager and excited to learn and develop my skills in iOS development. I was assigned this task as part of the recruitment process for the iOS Developer Intern position at OpeninApp. Due to my current lack of experience and access to a macOS development environment, I am unable to complete the task fully. However, I have outlined my approach and understanding of the task below. 
## Task Breakdown
The task involves creating UI components using SwiftUI to display data from an API. The specific requirements are:
1. Display a greeting based on the local time.
2. Create a chart from the given API response.
3. Add a tab view with "Top Links" and "Recent Links" and create list views to display the data from the API response.

## Steps to Complete the Task

### 1. Environment Setup
To develop an iOS app using SwiftUI, you need a macOS environment with Xcode installed. I would use a cloud-based macOS service such as MacinCloud or MacStadium to set up the environment and install Xcode.

### 2. Creating a SwiftUI Project
- Open Xcode.
- Create a new project by selecting `File > New > Project`.
- Choose `App` under the iOS tab and click `Next`.
- Name the project (e.g., `TaskDashboard' ensure `SwiftUI` is selected for the user interface.

### 3. Fetching Data from the API
- Create a new Swift file to handle API requests.
- Use URLSession to perform the network request and decode the JSON response into a Swift structure.
- Store the API response in an observable object to update the UI dynamically.

#### [API Service Code](https://gist.github.com/Varshithays/7cd92d17dfb45d712158821c69e6306d)

### 4. Displaying a Greeting Based on Local Time
- Create a SwiftUI view that determines the current hour and displays an appropriate greeting message.
- Use Swift's `Calendar` API to get the current hour and a 'Text' view to display the greeting.

#### [Greeting View Code](https://gist.github.com/Varshithays/8ea02a723546192143bfeabdcacb4d12)

### 5. Creating a Chart
- Install a SwiftUI-compatible charting library using Swift Package Manager.
- Create a SwiftUI view to display the chart using the data from the API response.

#### [Chart View Code](https://gist.github.com/Varshithays/365e5f48256280176b07ff796a9a72c3)

### 6. Tabs for Top Links and Recent Links
- Create the main content view with a `TabView` to switch between "Top Links" and "Recent Links".
- Use `List` views to display the links fetched from the API.

#### [Content View Code](https://gist.github.com/Varshithays/740aa2dff8da3a19ebef83ce66339b53)

## Conclusion
This document outlines my approach to the SwiftUI task. Although I am unable to implement the solution at this time, I hope this demonstrates my understanding of the requirements and my ability to plan and structure a solution. I am eager to learn and develop my skills in iOS development, and I appreciate your consideration.

Best regards,  
Varshitha Y S
