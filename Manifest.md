# Manifest


* Step 1: Introduction to the Manifest
  - Explain the concept of the manifest file in Android, which is an XML file that describes essential information about the application, its components, permissions, and required hardware/software features.
  - Describe the role of the manifest file in the Android operating system, as it is used by the system to identify and launch the application's components.

* Step 2: Basic Structure of the Manifest File
  - Introduce the basic structure of the manifest file, including the root element <manifest> and its attributes like package (unique identifier for the application) and android:versionCode/android:versionName (version information).
  - Discuss the <application> element, which encapsulates the entire application and contains various attributes and child elements.

* Step 3: Application Components
  - Explain the different components of an Android application, such as activities, services, broadcast receivers, and content providers.
  - Demonstrate how to declare these components in the manifest file using the appropriate XML elements (<activity>, <service>, <receiver>, <provider>).
  
* Step 4: Intent Filters
  - Discuss the concept of intent filters and how they enable components to respond to specific types of intents.
  - Show how to define intent filters for activities, services, and broadcast receivers using the <intent-filter> element within their respective XML declarations.
  - Provide examples of common intent filters like ACTION_MAIN and CATEGORY_LAUNCHER for the application's main activity.

* Step 5: Permissions
  - Introduce the concept of permissions in Android, which control the access to sensitive device resources or protected data.
  - Explain how to declare permissions required by the application using the <uses-permission> element in the manifest file.
  - Provide examples of common permissions like INTERNET, ACCESS_NETWORK_STATE, or custom permissions if relevant.

* Step 6: Other Manifest Features
  - Discuss additional manifest features like uses-sdk, uses-library, meta-data, etc., as per your curriculum or specific requirements.

* Step 7: Practical Exercises and Projects
  - Assign practical exercises to your students, such as creating a simple Android application with multiple components and appropriate manifest declarations.
  - Encourage them to experiment with different manifest settings, intent filters, and permissions to gain a better understanding of their usage.
  
> Resources:
>
> Official Android Documentation: Manifest File - https://developer.android.com/guide/topics/manifest/manifest-intro 
>
> Android Developers Codelabs: Manifest File - https://developer.android.com/codelabs/basic-android-kotlin-training-introduction-manifest
>
> Declaring Permissions: https://developer.android.com/guide/topics/permissions/overview
>
> Intent Filters: https://developer.android.com/guide/components/intents-filters
