# Week 1: Kotlin Basics - Pathway 1

<!-- 
Students may come to this class with little to no knowledge of the Android platform, how it is distinguished from other mobile app platforms, and how what they have already learned about coding, computational thinking and design and development relate to Android app development. Therefore, the main conceptual goals this week are to disambiguate between Android and other platforms and between Kotlin and Java (and other languages). Purely technical goals include installing Android Studio, creating a first basic app and running it on a properly configured AVD. 

Since this is the first class of the course it will be necessary to go over the syllabus and any related content. Ideally, this takes only a short amount of time so that time can be spent addressing first course content. Since this is the first class, and because of the requirements of discussing the syllabus, I forgo any lab component for this week. Providing optional activities (codelabs) or readings is appropriate. -->

## Welcome to the First Week of Kotlin for Android Development!

This week, we’ll kick off our journey into Kotlin and Android development. Whether you’re new to Android or have limited exposure to mobile app platforms, this class is designed to help you start with confidence. Here's what you can expect:

### What You’ll Learn <!-- {docsify-ignore} -->
- **Understanding Platforms:** Gain clarity on what makes Android unique compared to other mobile app platforms like iOS or cross-platform frameworks.
- **Kotlin vs. Java:** Explore how Kotlin differs from Java and other programming languages, and why it’s the preferred choice for Android development.
- **Setting Up Your Tools:** Install Android Studio, configure an Android Virtual Device (AVD), and create your first basic Android app!

### First Steps <!-- {docsify-ignore} -->
Since this is our introductory class, we’ll also review the course syllabus, expectations, and resources. This will give you a clear roadmap for the weeks ahead. We’ll keep this part brief so we can dive into the exciting world of Kotlin and Android as soon as possible.

### Optional Activities <!-- {docsify-ignore} -->
To reinforce what you learn this week, optional activities such as codelabs and recommended readings will be provided. These will help you explore and experiment at your own pace.

## Lecture Plan
| Activity  | Topic  | Time Alloted  | Details  |
| :----------:  | :----------:  | :----------:  | :----------  |
| Lecture  | Course Welcome  | 30 minutes  | Just cover course-specific content and won't need to cover Brightspace organization (i.e. follow DGL practices for course shell organization).   |
| Lecture  | The Android platform  | 15 minutes  |   |
| Walkthrough  | Install Android Studio  | 10 minutes  |   |
| Walkthrough  | Create a new AVD  | 5 minutes  |   |
| Activity  | Create a new AVD  | 10 minutes  | Consider recommendations for device coverage (such as, large screen, foldable, or older device)  |
| Walkthrough  | Create and run a new Empty project  | 10 minutes  | **Template differences**, **Naming conventions**, **Correct settings**   |
| Activity  | Create a new Basic (or other) project  | 15 minutes  | Explore the other template options (suc as, creating a new Basic project)  |
| Walkthrough  | Push code to GitHub  | 15 minutes  | Include links and directions to install GitHub Desktop if necessary  |
| Lecture  | The Kotlin language  | 15 minutes  |   |
| Walkthrough  | Kotlin playground Hello World!  | 10 minutes  |   |
| Activity  | Write your own Kotlin code!  | 15 minutes  |   |
| Lecture  | Documentation resources  | 15 minutes |   |
| Activity  | Find documentation  | 15 minutes  |   |


## How this week's course components will help you to achieve the learning outcome <!-- {docsify-ignore} -->
| Weekly terminal behaviour  | Supports learning outcome  | Composed of content |
| :---:         |     :---:      |          :---: |
| Contrast Android platform from other major mobile app platforms (i.e., iOS, web)    |      |     |
| Install Android Studio and configure at least one AVD     | configure an Integrated Development Environment (IDE) for mobile app development       | Configuring the Integrated Development Environment (IDE)      |
| Create a new Android Studio project and run the project     | produce app user interfaces using both IDE tools and programmatic approach       | Fundamental mobile app architectural components      |
| Push code up to class GitHub organization     |        |       |
| State basic differences between Java and Kotlin languages     | apply appropriate programmatic components from relevant APIs       | Platform-specific language fundamentals      |
| Identify online documentation sources and development references/supports     | apply appropriate programmatic components from relevant APIs       | Platform-specific language fundamentals      |

## Vocabulary <!-- {docsify-ignore} -->
| Concepts  | Kotlin/Android artifacts  |
| ----------  | ----------  |
| Android  |   |
| Android app  |   |
| Android device  |   |
| Android emulator |   |
| Android Virtual Device (AVD) |   |
| Android Studio |   |
| Code (Source code)  |   |
| IDE (Integrated Development Environment)  |   |
| Kotlin  |   |
| Reference  |   |

### What’s Next? <!-- {docsify-ignore} -->
While there’s no lab component this week, you’ll walk away with a solid understanding of the Android platform, have your development environment set up, and take the first step in creating Android apps.

## Lab Activity
> The link of the activity: [Link](https://developer.android.com/courses/pathways/android-basics-compose-unit-1-pathway-1#codelab-https://developer.android.com/codelabs/basic-android-kotlin-compose-first-program)

### 1. Before you Begin

In this lab activity,  you will build apps by writing code in the Kotlin programming language, which is the language recommended by Google when creating new Android apps.

> #### What is Kotlin?
> Kotlin is a modern programming language that helps developers be more productive. For example, Kotlin allows you to be more concise and write fewer lines of code for the same functionality compared to other programming languages. Apps that are built with Kotlin are also less likely to crash, resulting in a more stable and robust app for users. Essentially, with Kotlin, you can write better Android apps in a shorter amount of time. As a result, Kotlin is gaining momentum in the industry and is the language that the majority of professional Android developers use.

To get started on building Android apps in Kotlin, it's important to first establish a solid foundation of programming concepts in Kotlin. With the codelabs in this pathway, you will learn about Kotlin programming basics before diving into app creation.

> ### What you'll build
> Short programs in Kotlin that display messages when you run them.

>  ### What you'll build
>   - How to write and run a simple Kotlin program.
>   - How to modify a simple program to change the output.

### What you'll need
A computer with internet access and a web browser.

### 2. Get Started
In this lab activity, you'll explore and modify simple programs in Kotlin. You can think of a program as a series of instructions for a computer or mobile device to perform some action, such as display a message to a user or calculate the cost of items in a shopping cart. The step-by-step instructions for what the computer should do is called code. When you modify the code in a program, the output can change.

You use a tool called a code editor to write and edit your code. It's similar to a text editor in which you can write and edit text, but a code editor also provides functionality to help you write code more accurately. For example, a code editor shows autocomplete suggestions while you type, and displays error messages when code is incorrect.

To practice the basics of the Kotlin language, you will use an interactive code editor called the Kotlin Playground. You can access it from a web browser, so you don't need to install any software on your computer. You can edit and run Kotlin code directly in the Kotlin Playground and see the output.

Note that you can't build Android apps within the Kotlin Playground. In later tasks, you will install and use a tool called **Android Studio** to write and edit your Android app code.

Now that you have some context on Kotlin, take a look at your first program!

### 3. Open Kotlin Playground

In a web browser on your computer, open the [Kotlin Playground](https://play.kotlinlang.org/).

You should see a web page similar to this image:

