# Android Course


#### An Android Basics in Kotlin! In this course, you'll learn the basics of building Android apps with the Kotlin programming language. Along the way, you'll develop an app to start your journey as an Android developer.


| Units  | Cocepts  |
| ------------ | ------------ |
| Unit 1  | [Install Android Stadio and Tools](#-install-android-stadio-and-tools)  |
| Unit 2  | [Layouts](#-layouts)  |
| Unit 3  | [UI/UX Design](#-uiux-design)  |
| Unit 4  | [Introduction to Kotlin](#-introduction-to-kotlin)  |
| Unit 5  | [Access views in Android](#-access-views-in-android)  |
| Unit 6  | [Lists and Adapters](#-lists-and-adapters-in-android)  |
| Unit 7  | [Data Persistence and Networking](#-data-persistence-and-networking)  |
| Unit 8  |  [Fragments](#-fragments)  |
| Unit 9  | [Navigation](#-navigation)  |
| Unit 10  | [Asesets](#-fragments)  |
| Unit 11  | [Image Loaders](#-image-loaders)  |
| Unit 12  |  [Storage](#-storage)  |
| Unit 13  |  [Map](#-map-in-android)  |
| Unit 14  |  [DI](#-dependency-injection-in-android)  |
| Unit 15  |  [Git](#-git-version-control-system)  |
| Unit 16  |  [Notification](#-notifications)   |
| Unit 17  |  [ ]()  |
| Unit 18  |  [ ]()  |
| Unit 19  |  [ ]()  |
| Unit 20  |  [ ]()  |
------------

[Figma](https://www.figma.com/file/O9kcOlYhmlRjSnxU64C18d/learn-android?type=design&node-id=1%3A9&mode=design&t=YWZmocQtdUF6D2Ko-1)


### 🛠 Install Android Stadio and Tools
* Step 1: Introduction to Android Studio
  - Begin by introducing Android Studio as the official integrated development environment (IDE) for Android app development.
  - Explain its features, including code editing, debugging, and visual layout design.
  - Discuss the benefits of using Android Studio for Android development.
  - Resources: [Android official page](https://www.android.com/),  
* Step 2: System Requirements
  - Explain the system requirements for installing Android Studio, such as the supported operating systems, minimum RAM, and disk space.
  - Emphasize the importance of meeting these requirements to ensure smooth installation and usage of Android Studio.
* Step 3: Download Android Studio
  - Go to the official Android Studio website: [https://developer.android.com/studio](https://developer.android.com/studio)
  - How to navigate to the "Download" section of the website.
  - Guide to select the appropriate version of Android Studio for their operating system (Windows, macOS, or Linux).
* Step 4: Install Android Studio
  - How to install Android Studio based on the operating system they are using.
  - Walk through the installation wizard, including selecting the installation location and accepting the terms and conditions.
  - Explain the optional components and recommend installing the ones relevant to their development needs.
  - Resources: [Install Android Studio](https://developer.android.com/studio/install)
* Step 5: Configure Android Studio
  - Once the installation is complete, guide through the initial setup and configuration process.
  - Choose the Android SDK (Software Development Kit) components they want to install.
  - How to set up a virtual device (emulator) for testing Android apps.
  - Resources: [JDK](https://www.oracle.com/java/technologies/downloads/)
* Step 6: Verify Installation
  - Launch Android Studio and verify that it opens without any errors.
  - Explore the various features and components of the Android Studio IDE, such as the project structure, code editor, and emulator.
  - Resources: [Get to know the Android Studio UI](https://developer.android.com/studio/intro/user-interface), [Keyboard shortcuts](https://developer.android.com/studio/intro/keyboard-shortcuts)
* Run an AVD (Android Virtual Device) emulator
* Configure the project with [Gradle](Gradle.md)

> Create the first application to display "Hello World!"


------------


### 🏢 Layouts
* Introduction to Layouts:
   - Purpose of layouts and how they help in organizing and positioning UI elements in an Android app.
   - Basic structure of an XML layout file in Android.
   - Common XML tags like [`<LinearLayout>`](https://developer.android.com/reference/android/widget/LinearLayout), [`<RelativeLayout>`](https://developer.android.com/reference/kotlin/android/widget/RelativeLayout), [`<ConstraintLayout>`](https://developer.android.com/reference/kotlin/androidx/constraintlayout/widget/ConstraintLayout), etc.
   - How to define UI elements (views) and arrange them using XML attributes.
   - Resource: Android Developer Documentation - [User Interface Overview](https://developer.android.com/develop/ui), [XML Layouts](https://developer.android.com/guide/topics/ui/declaring-layout), UI Guids: [LinearLayout](https://developer.android.com/develop/ui/views/layout/linear), [RelativeLayout](https://developer.android.com/develop/ui/views/layout/relative), [ConstraintLayout](https://developer.android.com/develop/ui/views/layout/constraint-layout).
* XML Layouts:
   - Introduce **XML** as the **[markup language](https://en.wikipedia.org/wiki/Markup_language)** used to define layouts in Android.
   - Teach how to create XML layout files, including the root element, [namespaces](https://www.geeksforgeeks.org/xml-namespaces-in-android/), and attributes.
   - Resource: Android Developer Documentation - [Layouts in XML](https://developer.android.com/develop/ui/views/layout/declaring-layout)
* ViewGroups and View Hierarchy:
   - Discuss the concept of ViewGroup as a container for UI elements.
   - Explain the view hierarchy and how views are nested within ViewGroup containers.
   - Resource: Android Developer Documentation - [ViewGroup](https://developer.android.com/reference/android/view/ViewGroup)
* Linear Layout:
   - Explore the <LinearLayout> tag and its attributes for arranging views linearly.
   - Teach concepts like orientation (horizontal or vertical), weight, and gravity.
   - Demonstrate how to nest layouts and views within a linear layout.
   - Resources: Android Developer Documentation - [LinearLayout](https://developer.android.com/reference/android/widget/LinearLayout)
* Constraint Layout:
   - Discuss the benefits of using <ConstraintLayout> for complex UI designs.
   - Teach the concept of constraints and how to create relationships between views.
   - Cover attributes like app:layout_constraintStart_toStartOf, app:layout_constraintEnd_toEndOf, etc.
   - Resources: Android Developer Documentation - [Constraint Layout](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout)
*Advanced Layout Techniques:
   - Explore more advanced topics like using nested layouts, incorporating scrollable views (e.g., `<ScrollView>`, `<RecyclerView>`), and handling different screen sizes and orientations.
   - Discuss best practices for optimizing layouts and improving performance.
   - Resources: Android Developer Documentation - [ScrollView](https://developer.android.com/reference/android/widget/ScrollView), [RecyclerView](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView)
* Explain the concept of the manifest file in Android [Manifest](Manifest.md)
* Explain the concept of theme and style in Android [theme and style](Theme.md)
* Explain the resources in android [Resources](Resources.md)

> Practice App Idea: Build a User Interface of app.


------------


### 🍰 UI/UX Design
1. **Learn the fundamentals of UX design**: This will give you a solid foundation of the principles, methods, and processes of UX design. You will learn how to empathize with users, define problems, ideate solutions, prototype and test designs, and iterate based on feedback. Some resources you can use to learn UX design fundamentals are:
    - [Coursera: UI/UX Design Specialization](https://www.coursera.org/specializations/ui-ux-design)
    - [Udemy: User Experience Design Essentials - Adobe XD UI UX Design](https://www.udemy.com/course/ui-ux-web-design-using-adobe-xd/)
    - [Interaction Design Foundation: UX Design Courses](https://www.interaction-design.org/courses)
2. **Learn the fundamentals of UI design**: This will give you a solid foundation of the principles, elements, and tools of UI design. You will learn how to create visually appealing and functional interfaces that match the user needs and expectations. You will also learn how to use design systems, guidelines, and patterns to ensure consistency and usability. Some resources you can use to learn UI design fundamentals are:
    - [Coursera: Visual Elements of User Interface Design](https://www.coursera.org/learn/ui-design)
    - [Udemy: UI & Web Design using Adobe Illustrator CC](https://www.udemy.com/course/ui-web-design-using-adobe-illustrator/)
    - [Skillshare: UI/UX & Web Design using Adobe XD](https://www.skillshare.com/classes/UIUX-Web-Design-using-Adobe-XD/1910638556)
3. **Learn the tools and software of UI/UX design**: This will give you a practical knowledge of how to use various tools and software to create and communicate your UI/UX designs. You will learn how to use tools such as **[Sketch](https://www.sketch.com/)**, **[Figma](https://www.figma.com)**, **[Adobe XD](https://www.adobe.com/products/xd.html)**, Photoshop, Illustrator, etc., to create wireframes, mockups, prototypes, icons, graphics, etc. You will also learn how to use tools such as InVision, Marvel, Balsamiq, etc., to collaborate and share your designs with others. Some resources you can use to learn UI/UX design tools and software are:
    - [Coursera: UI / UX Design with Adobe XD Ecosystem](https://www.coursera.org/learn/ui-ux-design-with-adobe-xd-ecosystem)
    - [Udemy: The Complete Sketch 5 Course - Design Apps & Websites 2021](https://www.udemy.com/course/sketchdesign/)
    - [Skillshare: Figma for Beginners: Learn UI/UX Design from Scratch](https://www.skillshare.com/classes/Figma-for-Beginners-Learn-UIUX-Design-from-Scratch/1258850005)
4. **Build a portfolio of UI/UX design projects**: This will give you a chance to apply your skills and knowledge to real-world problems and showcase your work to potential employers or clients. You will learn how to choose projects that demonstrate your value and expertise, how to document your design process and decisions, and how to present your designs effectively. Some resources you can use to build a UI/UX design portfolio are:
    - [Coursera: Build a Professional Portfolio with Adobe XD](https://www.coursera.org/projects/build-a-professional-portfolio-with-adobe-xd)
    - [Udemy: How To Create A UX/UI Portfolio With No Experience](https://www.udemy.com/course/how-to-create-a-uxui-portfolio-with-no-experience/)
    - [Skillshare: How To Create A Stunning Portfolio Website As A Web Developer](https://www.skillshare.com/classes/How-To-Create-A-Stunning-Portfolio-Website-As-A-Web-Developer/2130441899)
5. **Keep learning and improving your UI/UX design skills**: This will help you stay updated with the latest trends and technologies in the UI/UX field and expand your knowledge and abilities. You will learn how to follow industry best practices, how to learn from other designers and experts, how to find inspiration and resources, and how to challenge yourself with new projects and skills. Some resources you can use to keep learning and improving your UI/UX design skills are:
    - [Coursera: Advanced UX Research & Strategy](https://www.coursera.org/specializations/advanced-ux-research-strategy)
    - [Udemy: Mobile App Design In Sketch 3: UX and UI Design From Scratch](https://www.udemy.com/course/mobile-app-design-in-sketch-3-ux-and-ui-design-from-scratch/)
    - [Skillshare: UI Animation Fundamentals & Micro-interactions in After Effects](https://www.skillshare.com/classes/UI-Animation-Fundamentals-Micro-interactions-in-After-Effects/1560151896)
- Introduce some UI websites like: **[Dribble](https://dribbble.com/)**, **[UI8](https://ui8.net/)**, **[Mobbin](https://mobbin.com/)**, **[Uplabs](https://www.uplabs.com/)**
- Introduce trend UI
- [Material's Communication Principles: Codelab- Intro to UX Writing](https://codelabs.developers.google.com/codelabs/material-communication-guidance)
- [Material's Communication Principles](https://m2.material.io/design/communication/confirmation-acknowledgement.html)
- [Google UX Design Certificate](https://learndigital.withgoogle.com/digitalworkshop-eu/course/gccs-ux-design)




------------

  
### 🟪 Introduction to Kotlin
* Download intellij [Link](https://www.jetbrains.com/idea/download)  
* Teach the basics of Kotlin syntax, including Variables, Basic types, Collections, Control flow, Functions, Classes, Null safety.
* Resources: [Kotlin Programming Language Documentation](https://kotlinlang.org/docs/home.html), [Kotlin Koans](https://play.kotlinlang.org/koans/overview)<br>
* Step 1: Introduction to Kotlin Basics
  - Variables, data types, and type inference
  - Control flow statements (if-else, when, loops)
  - Functions and lambdas
  - Nullable types and null safety
  - String interpolation
* Step 2: Object-Oriented Programming (OOP) in Kotlin
  - Classes, objects, and instances
  - Properties and fields
  - Constructors and initialization
  - Inheritance and overriding
  - Interfaces and abstract classes
  - Access modifiers (public, private, protected)
* Step 3: Functional Programming in Kotlin
  - Higher-order functions
  - Lambda expressions and function literals
  - Function composition and pipelining
  - Collections and operations (map, filter, reduce)
  - Kotlin standard library functions (let, run, with, apply)
* Step 4: Extension Functions and Operator Overloading
  - Extension functions and properties
  - Extension functions on Android classes (e.g., View)
  - Operator overloading (e.g., plus, minus, equals)
* Step 5: Null Safety and Smart Casts
  - Nullable types and safe calls
  - Elvis operator and safe casting
  - Type checks and smart casts
  - Non-null assertions and lateinit
* Step 6: Coroutines and Asynchronous Programming
  - Introduction to coroutines and suspending functions
  - Coroutine builders (launch, async)
  - Coroutine context and dispatchers
  - Structured concurrency and cancellation
  - Error handling in coroutines
 
Video Resources:
[Kotlin Tutorial with Donn Felker](https://www.youtube.com/watch?v=wuiT4T_LJQo)


------------


### 🏢 Access views in Android
- Introduction to View Objects:
  - Explain what view objects are in the context of Android development.
  - Introduce commonly used view classes such as TextView, Button, ImageView, etc.
  - Teach how to create views programmatically using the corresponding view class.
  - Resources: Android Developer Documentation on [Views](https://developer.android.com/reference/android/view/View)
- Referencing Views in XML Layouts:
  - Explain how to assign an ID to a view in XML using the android:id attribute.
  - Teach how to reference views from XML layouts in the Java/Kotlin code using the findViewById() method.
  - Resources: Android Developer Documentation on [findViewById()](https://developer.android.com/reference/android/view/View#findViewById(int))
- ButterKnife Library (Optional):
  - Introduce the ButterKnife library, which simplifies view binding and reduces boilerplate code.
  - Teach how to use annotations to bind views in the code using ButterKnife.
  - Resources: [ButterKnife GitHub Repository](https://github.com/JakeWharton/butterknife)
- View Binding (Recommended):
  - Explain the concept of view binding, a feature introduced by Android to eliminate the need for findViewById().
  - Teach how to enable view binding in an Android project and access views using generated binding classes.
  - Resources: Android Developer Documentation on [View Binding](https://developer.android.com/topic/libraries/view-binding)
- Data Binding (Advanced):
  - Introduce data binding, a powerful feature that allows for seamless interaction between views and data models.
  - Teach how to enable data binding in an Android project and use binding expressions to bind data to views.
  - Resources: Android Developer Documentation on [Data Binding](https://developer.android.com/topic/libraries/data-binding)
- Kotlin Synthetic Properties (Kotlin Only):
  - Explain Kotlin synthetic properties, which provide a concise way to access views directly in Kotlin code without findViewById().
  - Teach how to enable synthetic properties in a Kotlin project and access views using their IDs as property names.
  - Resources: [Kotlin Synthetic Properties Documentation](https://kotlinlang.org/docs/synthetic-properties.html)

> Practice accessing views in different scenarios and building small projects that involve manipulating views dynamically.

------------


### 📃 Lists and Adapters in Android
* Step 1: Introduction to RecyclerView
  - Explain the purpose and benefits of using RecyclerView for displaying lists in Android.
  - Familiarize students with the RecyclerView component and its advantages over ListView.
  - Introduce the concept of a data source for the RecyclerView.
  - Resources: Android Developer Documentation on [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)
* Step 2: Creating a Custom Adapter
  - Explain the role of an adapter in connecting data to the RecyclerView.
  - How to create a custom adapter by extending the RecyclerView.Adapter class.
  - Implementing the necessary methods such as `onCreateViewHolder()` and `onBindViewHolder()`.
  - Resources: Android Developer Documentation on [Adapter](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.Adapter)
  - Code Lab: RecyclerView [Google Codelabs](https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view)
* Step 3: Understanding ViewHolders
  - Introduce the ViewHolder pattern and its importance for optimizing RecyclerView performance.
  - How to create a ViewHolder class to cache references to the views within each item in the list.
  - Explain the process of binding data to the ViewHolder views in `onBindViewHolder()`.
  - Resources: Android Developer Documentation on [ViewHolder](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.ViewHolder)
* Step 4: Data Model and Item Layout
  - Creating a data model class to represent the individual items in the list.
  - How to create an item layout XML file to define the visual representation of the list items.
  - How to inflate the item layout in `onCreateViewHolder()` and bind data in `onBindViewHolder()`.
* Step 5: Click Listeners and User Interaction
  - How to implement click listeners for items in the RecyclerView.
  - How to handle item click events and perform actions based on the clicked item.
  - Discuss other forms of user interaction, such as long-click listeners or swipe gestures.
  - Resources: Android Developer Documentation on [Handling Click Events](https://developer.android.com/guide/topics/ui/controls/button#kotlin)
  - Code Lab: Clickable Images in RecyclerView [Google Codelabs](https://codelabs.developers.google.com/codelabs/kotlin-android-training-clickable-images)
* Step 6: Advanced Topics and Enhancements
  - Cover topics such as handling different view types within the RecyclerView (e.g., headers, footers), implementing item animations, or integrating   - search functionality.
  - Resources: Android Developer Documentation on [RecyclerView Animations](https://developer.android.com/training/animation/reveal-or-hide-view)

> Google Codelab for [RecyclerView and Adapters](https://codelabs.developers.google.com/codelabs/kotlin-android-training-recyclerview-fundamentals "RecyclerView and Adapters")
> Practice create a list of products of build a To-Do app.


------------


### 🏢 Data Persistence and Networking


------------
  
  
### 🔳 Fragments
* Step 1: Introduction to Fragments
  - Explain the concept of Fragments in Android and their purpose in creating flexible and reusable UI components.
  - Introduce the Fragment lifecycle and explain the different states a Fragment can be in.
  - Provide an overview of how Fragments can be used in various screen sizes and orientations.
  - References:
Android Developer Documentation: Fragments - https://developer.android.com/guide/fragments
Android Fragment Basics - https://developer.android.com/guide/components/fragments

* Step 2: Creating a Fragment
  - Show how to create a new Fragment class by extending the Fragment class.
  - Explain the necessary methods to override, such as onCreateView() for creating the Fragment's layout.
  - Demonstrate how to inflate a layout file and return the inflated View from onCreateView().
  - Codelabs:
  Android Fragments Codelab - https://codelabs.developers.google.com/codelabs/building-android-ui-with-fragments

* Step 3: Adding a Fragment to an Activity
  - Illustrate how to add a Fragment to an Activity's layout using XML or programmatically.
  - Discuss different strategies for including Fragments in an Activity, such as FragmentTransaction and FragmentManager.
  - Show how to handle Fragment transactions, such as adding, replacing, or removing Fragments dynamically.
  - Samples:
  Fragment Basics Sample - https://github.com/android/fragment-basics-samples

* Step 4: Communicating between Fragments and Activities
  - Explain how to establish communication between Fragments and their hosting Activities.
  - Introduce the use of interfaces to define callbacks and establish communication channels.
  - Demonstrate how to send data from a Fragment to an Activity and vice versa.
  - References:
    Communicating with Other Fragments - https://developer.android.com/guide/fragments/communicate

* Step 5: Handling Fragment Lifecycles
  - Dive deeper into the Fragment lifecycle and discuss the various methods available, such as onAttach(), onResume(), onPause(), etc.
  - Explain how to handle configuration changes, like screen rotations, without losing Fragment state.
  - Provide best practices for managing the Fragment lifecycle effectively.
  - References:
    Fragment Lifecycle - https://developer.android.com/guide/fragments/lifecycle

* Step 6: Using Fragment Manager and Backstack
  - Introduce the Fragment Manager and Backstack to manage Fragments in an Activity.
  - Explain how to handle Fragment transactions and navigate the Backstack.
  - Discuss techniques for handling Fragment navigation, such as using addToBackStack() and popBackStack().
  - References:
    FragmentManager - https://developer.android.com/reference/androidx/fragment/app/FragmentManager
    FragmentManager.BackStackEntry - https://developer.android.com/reference/androidx/fragment/app/FragmentManager.BackStackEntry



 - Fragment Lifecycle
 - FragmentTransaction
 - Pass Arguments to fragment
 - DialogFragment
 - BottomSheet Dialog Fragment
 - ViewPager
  
  
------------

### 🧭 Navigation

------------


### 🖼 Assets  - Shaps
 **Aim:**   Create an introductory page and direct it to the main page for navigation.<br/>
 - Intro [Shapes](https://developer.android.com/reference/kotlin/androidx/compose/material/Shapes)


------------


### 🖼 Image Loaders


------------


### 📅 Storage
  
  
------------


### 🗺 Map in Android


------------


### 💉 Dependency Injection in Android


------------


### 🟠 Git (Version Control System)


------------


### 🔉 Notifications


