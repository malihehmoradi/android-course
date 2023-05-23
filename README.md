# Android Course


#### An Android Basics in Kotlin! In this course, you'll learn the basics of building Android apps with the Kotlin programming language. Along the way, you'll develop an app to start your journey as an Android developer.


| Units  | Cocepts  |
| ------------ | ------------ |
| Unit 1  | Introduction to Android Development  |
| Unit 2  | UI-UX  |
| Unit 3  | Layouts in Android  |
| Unit 4  | Introduction to Kotlin  |
| Unit 5  | Access views in Android  |
| Unit 6  | Lists and Adapters  |
| Unit 7  | Data Persistence and Networking  |
| Unit 8  |  Fragments  |
| Unit 9  | Navigation  |
| Unit 10  | Asesets  |
| Unit 11  | Image Loaders  |
| Unit 12  |  Storage  |
| Unit 13  |  Map  |
| Unit 14  |  Map  |
| Unit 15  |  DI  |
| Unit 16  |  Git  |
| Unit 17  |  Notification  |
------------

### Unit 1: Introduction to Android Development
- **Android:**
  - Introduce [Android](https://www.android.com/)
  - Why do we choose Android?
  - How to make money from Android programming?
  - Introduce [Android Studio](https://developer.android.com/studio)
  - Android programming requirements' tools
  - Introduce Emulators (AVD, Genymotion, Bluestacks)
  - Install AVD
- **Kotlin:**
  - Introduce [Kotlin](https://kotlinlang.org/)
  - Why do we choose Kotlin?
- **Requirements:**
  - Download the last version of Android Studio from this link: [Android Studio](https://developer.android.com/studio)
  - Download the last version of JDK from this link: [JDK](https://www.oracle.com/java/technologies/downloads/)

> Practice App Idea: Create a simple "Hello, Android" app that displays a welcome message on the screen.

------------


### Unit 2: UI-UX  - Introduce an instance app
- **UI**
  - Introduce some UI-UX design tools like: **[Figma](https://www.figma.com)**, **[Adobe XD](https://www.adobe.com/products/xd.html)**, **[Sketch](https://www.sketch.com/)** and work with them
  - Introduce some UI websites like: **[Dribble](https://dribbble.com/)**, **[UI8](https://ui8.net/)**, **[Mobbin](https://mobbin.com/)**, **[Uplabs](https://www.uplabs.com/)**
  - Introduce trend UI


------------


### Unit 3: 🏢 Layouts in Android
- Introduction to Layouts:
   - Explain the purpose of layouts and how they help in organizing and positioning UI elements in an Android app.
   - Understand the basic structure of an XML layout file in Android.
   - Learn about common XML tags like `<LinearLayout>`, `<RelativeLayout>`, `<ConstraintLayout>`, etc.
   - Explain how to define UI elements (views) and arrange them using XML attributes.
   - Resource: Android Developer Documentation - [User Interface Overview](https://developer.android.com/develop/ui), [XML Layouts](https://developer.android.com/guide/topics/ui/declaring-layout)
- XML Layouts:
   - Introduce **XML** as the **markup language** used to define layouts in Android.
   - Teach how to create XML layout files, including the root element, namespaces, and attributes.
   - Resource: Android Developer Documentation - [Layouts in XML](https://developer.android.com/develop/ui/views/layout/declaring-layout)
- ViewGroups and View Hierarchy:
   - Discuss the concept of ViewGroup as a container for UI elements.
   - Explain the view hierarchy and how views are nested within ViewGroup containers.
   - Resource: Android Developer Documentation - [ViewGroup](https://developer.android.com/reference/android/view/ViewGroup)
- Linear Layout:
   - Explore the <LinearLayout> tag and its attributes for arranging views linearly.
   - Teach concepts like orientation (horizontal or vertical), weight, and gravity.
   - Demonstrate how to nest layouts and views within a linear layout.
   - Resources: Android Developer Documentation - [LinearLayout](https://developer.android.com/reference/android/widget/LinearLayout)
- Relative Layout:
   - Introduce the <RelativeLayout> tag for creating more flexible UI layouts.
   - Explain how to position views relative to each other using attributes like layout_above, layout_below, layout_toLeftOf, etc.
   - Demonstrate the use of alignment attributes and margins in relative layouts.
   - Resources: Android Developer Documentation - [RelativeLayout](https://developer.android.com/reference/android/widget/RelativeLayout)
- Constraint Layout:
   - Discuss the benefits of using <ConstraintLayout> for complex UI designs.
   - Teach the concept of constraints and how to create relationships between views.
   - Cover attributes like app:layout_constraintStart_toStartOf, app:layout_constraintEnd_toEndOf, etc.
   - Resources: Android Developer Documentation - [Constraint Layout](https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout)
-Advanced Layout Techniques:
   - Explore more advanced topics like using nested layouts, incorporating scrollable views (e.g., `<ScrollView>`, `<RecyclerView>`), and handling different screen sizes and orientations.
   - Discuss best practices for optimizing layouts and improving performance.
   - Resources: Android Developer Documentation - [ScrollView](https://developer.android.com/reference/android/widget/ScrollView), [RecyclerView](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView)

> Practice App Idea: Build a User Interface of app.


------------


### Unit 4: Introduction to Kotlin
- Teach the basics of Kotlin syntax, including variables, data types, control flow statements (if-else, loops), and functions.
- Resources: [Kotlin Programming Language Documentation](https://kotlinlang.org/docs/home.html), [Kotlin Koans](https://play.kotlinlang.org/koans/overview)<br>
- Step 1: Introduction to Kotlin Basics
  - Variables, data types, and type inference
  - Control flow statements (if-else, when, loops)
  - Functions and lambdas
  - Nullable types and null safety
  - String interpolation
- Step 2: Object-Oriented Programming (OOP) in Kotlin
  - Classes, objects, and instances
  - Properties and fields
  - Constructors and initialization
  - Inheritance and overriding
  - Interfaces and abstract classes
  - Access modifiers (public, private, protected)
- Step 3: Functional Programming in Kotlin
  - Higher-order functions
  - Lambda expressions and function literals
  - Function composition and pipelining
  - Collections and operations (map, filter, reduce)
  - Kotlin standard library functions (let, run, with, apply)
- Step 4: Extension Functions and Operator Overloading
  - Extension functions and properties
  - Extension functions on Android classes (e.g., View)
  - Operator overloading (e.g., plus, minus, equals)
- Step 5: Null Safety and Smart Casts
  - Nullable types and safe calls
  - Elvis operator and safe casting
  - Type checks and smart casts
  - Non-null assertions and lateinit
- Step 6: Coroutines and Asynchronous Programming
  - Introduction to coroutines and suspending functions
  - Coroutine builders (launch, async)
  - Coroutine context and dispatchers
  - Structured concurrency and cancellation
  - Error handling in coroutines


------------


### Unit 5: 🏢 Access views in Android
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


### Unit 6: 📃 Lists and Adapters in Android
- Step 1: Introduction to RecyclerView
  - Explain the purpose and benefits of using RecyclerView for displaying lists in Android.
  - Familiarize students with the RecyclerView component and its advantages over ListView.
  - Introduce the concept of a data source for the RecyclerView.
  - Resources: Android Developer Documentation on [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)
- Step 2: Creating a Custom Adapter
  - Explain the role of an adapter in connecting data to the RecyclerView.
  - How to create a custom adapter by extending the RecyclerView.Adapter class.
  - Implementing the necessary methods such as `onCreateViewHolder()` and `onBindViewHolder()`.
  - Resources: Android Developer Documentation on [Adapter](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.Adapter)
  - Code Lab: RecyclerView [Google Codelabs](https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view)
- Step 3: Understanding ViewHolders
  - Introduce the ViewHolder pattern and its importance for optimizing RecyclerView performance.
  - How to create a ViewHolder class to cache references to the views within each item in the list.
  - Explain the process of binding data to the ViewHolder views in `onBindViewHolder()`.
  - Resources: Android Developer Documentation on [ViewHolder](https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.ViewHolder)
- Step 4: Data Model and Item Layout
  - Creating a data model class to represent the individual items in the list.
  - How to create an item layout XML file to define the visual representation of the list items.
  - How to inflate the item layout in `onCreateViewHolder()` and bind data in `onBindViewHolder()`.
- Step 5: Click Listeners and User Interaction
  - How to implement click listeners for items in the RecyclerView.
  - How to handle item click events and perform actions based on the clicked item.
  - Discuss other forms of user interaction, such as long-click listeners or swipe gestures.
  - Resources: Android Developer Documentation on [Handling Click Events](https://developer.android.com/guide/topics/ui/controls/button#kotlin)
  - Code Lab: Clickable Images in RecyclerView [Google Codelabs](https://codelabs.developers.google.com/codelabs/kotlin-android-training-clickable-images)
- Step 6: Advanced Topics and Enhancements
  - Cover topics such as handling different view types within the RecyclerView (e.g., headers, footers), implementing item animations, or integrating   - search functionality.
  - Resources: Android Developer Documentation on [RecyclerView Animations](https://developer.android.com/training/animation/reveal-or-hide-view)

> Google Codelab for [RecyclerView and Adapters](https://codelabs.developers.google.com/codelabs/kotlin-android-training-recyclerview-fundamentals "RecyclerView and Adapters")
> Practice create a list of products of build a To-Do app.


------------


### Unit 7: 🏢 Data Persistence and Networking


------------

### Unit 8: 🧭 Navigation

------------


### Unit 9:   🖼 Assets  - Shaps
 **Aim:**   Create an introductory page and direct it to the main page for navigation.<br/>
 - Intro [Shapes](https://developer.android.com/reference/kotlin/androidx/compose/material/Shapes)


------------


### Unit 10: Image Loaders


------------


### Unit 11:  Fragments
 - Fragment Lifecycle
 - FragmentTransaction
 - Pass Arguments to fragment
 - DialogFragment
 - BottomSheet Dialog Fragment
 - ViewPager

------------


### Unit 12: 📅 Storage
  
  
------------


### Unit 13: 🗺 Map in Android


------------


### Unit 14: 💉 Dependency Injection in Android


------------


### Unit 15:  Git (Version Control System)


------------


### Unit 16:  Notifications


