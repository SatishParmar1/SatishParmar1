<div align="center">

# 👨‍💻 Satish Parmar

### Flutter Developer | Code Architect | Innovation Enthusiast

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&multiline=false&repeat=true&width=600&height=100&lines=Building+Amazing+Mobile+Apps;Open+Source+Contributor;Flutter+Package+Publisher;IoT+%26+Blockchain+Explorer" alt="Typing SVG" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=200&section=header&text=Welcome%20To%20My%20Digital%20Space&fontSize=40&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Where%20Code%20Meets%20Creativity&descAlignY=52&descAlign=50" width="100%"/>

</div>

---

## 🌟 About Me

<img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif">

```typescript
const satish = {
    role: "Flutter Developer & Java Specialist",
    education: "B.Tech in Computer Science Engineering",
    location: "India 🇮🇳",
    passions: ["Mobile Development", "IoT", "Blockchain", "AI"],
    currentFocus: "Building cross-platform solutions",
    lifePhilosophy: "Code is poetry, bugs are typos",
    funFact: "I debug with console.log more than I admit 😄"
};
```

I'm a passionate developer who loves creating innovative solutions that make a real-world impact. From mobile apps to IoT systems, I enjoy exploring the intersection of hardware and software. Currently focused on building open-source Flutter packages and contributing to the developer community.

---

## 🔗 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satish-parmar-8021a5245/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/978satish)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:satishparmarparmar486@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)](https://who-is-satish.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SatishParmar1)

</div>

---

## 📦 My Published Packages

<div align="center">

### 🎯 Contributing to the Flutter Ecosystem

I believe in giving back to the community. Here are my published packages available on pub.dev:

</div>

<table>
<tr>
<td width="50%" valign="top">

### 🔄 Page Navigation Transition

[![pub package](https://img.shields.io/pub/v/page_navigation_transition.svg?label=pub&color=blue)](https://pub.dev/packages/page_navigation_transition)
[![likes](https://img.shields.io/pub/likes/page_navigation_transition?logo=flutter)](https://pub.dev/packages/page_navigation_transition/score)

**Version:** 1.1.0

A powerful Flutter package that provides smooth and customizable page transition animations for your mobile applications.

**✨ Features:**
- 🎨 Multiple transition styles (slide, fade, scale, rotate)
- ⚡ Highly customizable animations
- 📱 Works seamlessly with Navigator 2.0
- 🎯 Easy integration with existing Flutter apps
- 🔧 Minimal boilerplate code

**💡 Use Cases:**
- Enhanced user experience with smooth navigations
- Creating branded app transitions
- Building professional-looking mobile apps

```dart
// Quick Example
PageNavigationTransition(
  animationType: AnimationType.slideFromRight,
  duration: Duration(milliseconds: 300),
  child: YourNextPage(),
)
```

[📚 View Documentation](https://pub.dev/packages/page_navigation_transition) | [⭐ Star on GitHub](https://github.com/SatishParmar1)

</td>
<td width="50%" valign="top">

### 🖼️ Photo Opener View

[![pub package](https://img.shields.io/pub/v/photo_opener_view.svg?label=pub&color=blue)](https://pub.dev/packages/photo_opener_view)
[![likes](https://img.shields.io/pub/likes/photo_opener_view?logo=flutter)](https://pub.dev/packages/photo_opener_view/score)

**Version:** 1.1.0

An interactive and feature-rich photo viewer widget with zoom, pan, and gesture support for Flutter applications.

**✨ Features:**
- 🔍 Pinch to zoom functionality
- 👆 Smooth pan and swipe gestures
- 🎭 Hero animation support
- 📐 Customizable UI overlay
- 💾 Memory efficient image loading
- 🌙 Dark/Light mode support

**💡 Use Cases:**
- Gallery applications
- Social media photo viewers
- E-commerce product images
- Portfolio showcases

```dart
// Quick Example
PhotoOpenerView(
  imageUrl: 'your-image-url',
  enableZoom: true,
  backgroundColor: Colors.black,
)
```

[📚 View Documentation](https://pub.dev/packages/photo_opener_view) | [⭐ Star on GitHub](https://github.com/SatishParmar1)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ⭐ Smart Review Prompter

[![pub package](https://img.shields.io/pub/v/smart_review_prompter.svg?label=pub&color=blue)](https://pub.dev/packages/smart_review_prompter)
[![likes](https://img.shields.io/pub/likes/smart_review_prompter?logo=flutter)](https://pub.dev/packages/smart_review_prompter/score)

**Version:** 0.0.2

An intelligent in-app review prompting system that knows the perfect time to ask users for ratings, helping you boost your app's reviews without annoying users.

**✨ Features:**
- 🧠 Smart timing algorithms - prompts at the right moment
- 📊 Customizable trigger conditions (app launches, successful actions, time-based)
- 🎯 Non-intrusive user experience
- 📱 Native review dialogs (iOS App Store & Google Play)
- ⚙️ Fully configurable thresholds
- 💾 Persistent storage of user interactions
- 🚫 Respects user decisions (never ask again option)
- 📈 Analytics-friendly hooks

**💡 Use Cases:**
- Increasing app store ratings
- Gathering user feedback at optimal moments
- Building trust with non-aggressive prompting
- Improving app visibility through better reviews

**🎯 Smart Prompting Logic:**
```
✓ User has launched app X times
✓ User has completed Y successful actions
✓ Z days have passed since installation
✓ User hasn't been prompted in the last N days
✓ User hasn't clicked "never ask again"
```

```dart
// Quick Example
SmartReviewPrompter.instance.init(
  minLaunchCount: 5,
  minDaysSinceInstall: 3,
  remindDays: 7,
);

// Trigger when appropriate
if (await SmartReviewPrompter.instance.shouldPrompt()) {
  SmartReviewPrompter.instance.requestReview();
}
```

[📚 View Documentation](https://pub.dev/packages/smart_review_prompter) | [⭐ Star on GitHub](https://github.com/SatishParmar1)

</td>
</tr>
</table>

<div align="center">

### 📊 Package Stats

| Metric | Total |
|--------|-------|
| **Published Packages** | 3 |
| **Total Downloads** | 🔄 Growing |
| **Pub Points** | 🎯 High Quality |
| **Community Impact** | 🌟 Active |

**🎉 Want to contribute?** All packages are open source and accepting contributions!

</div>

---

## 🎯 What I'm Working On

<div align="center">

```mermaid
graph LR
    A[🎯 Current Focus] --> B[Smart Home IoT]
    A --> C[Blockchain Integration]
    A --> D[AI Vision Systems]
    A --> E[Flutter Packages]
    B --> F[ESP8266]
    C --> G[Solidity]
    D --> H[Assistive Tech]
    E --> I[Open Source]
```

</div>

### 🚀 Active Projects

- **🏠 Smart Home IoT + Blockchain** - Building a decentralized smart home control system
  - Tech: Flutter, ESP8266, Solidity, Firebase
  - Status: 🔨 In Development
  
- **🔍 Search UI Application** - Modern search interface with advanced filtering
  - Tech: Flutter, Provider, REST API
  - Status: ⚡ Optimizing

- **👁️ AI Vision Assistant** - Assistive technology for visually impaired users
  - Tech: Flutter, TensorFlow, IoT
  - Status: 🧪 Research Phase

### 🤝 Open to Collaborate On

- AI-powered mobile applications
- IoT integration projects
- Educational tech platforms
- Open source Flutter packages
- Student-Alumni networking systems

---

## 💻 Tech Stack

<div align="center">

### Languages
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### Frameworks & Libraries
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & Database
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

### IoT & Hardware
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Satish's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=SatishParmar1&theme=react-dark&hide_border=true&area=true)](https://github.com/SatishParmar1)

</div>

---

## 🎓 Learning Journey

<div align="center">

| Technology | Proficiency | Current Focus |
|-----------|-------------|---------------|
| Flutter & Dart | ███████████ 90% | Advanced State Management |
| Firebase | ████████░░░ 75% | Cloud Functions & Analytics |
| Java & Spring Boot | ███████░░░░ 65% | Microservices Architecture |
| Blockchain | ██████░░░░░ 55% | Smart Contracts & DApps |
| AI/ML | █████░░░░░░ 50% | TensorFlow & Computer Vision |
| IoT | ████████░░░ 70% | ESP8266 & Arduino Integration |

</div>

---

## 💡 Featured Repositories

<div align="center">

<a href="https://github.com/SatishParmar1/page_navigation_transition">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=SatishParmar1&repo=page_navigation_transition&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=6C63FF" />
</a>
<a href="https://github.com/SatishParmar1/photo_opener_view">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=SatishParmar1&repo=photo_opener_view&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=6C63FF" />
</a>

</div>

---

## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- 🚀 Building Reusable Flutter Packages: A Complete Guide
- 🎨 Mastering Custom Animations in Flutter
- 🔥 Firebase + Flutter: Real-time Chat Application
- 🤖 IoT meets Mobile: Controlling ESP8266 with Flutter
- 💎 Clean Architecture in Flutter: Best Practices
<!-- BLOG-POST-LIST:END -->

---

## 🎯 2025 Goals

- ✅ Publish 5+ Flutter packages on pub.dev
- 🔄 Contribute to 10+ open source projects
- 📚 Write technical blogs and tutorials
- 🎓 Master advanced Flutter animations
- 🚀 Build a complete AI-powered mobile app
- 🌟 Reach 1000+ GitHub stars across repositories
- 🤝 Mentor aspiring Flutter developers

---

## 💭 Random Dev Quote

<div align="center">

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>

---

<div align="center">

### 💖 Support My Work

If you find my packages useful, consider giving them a ⭐ on GitHub and a 👍 on pub.dev!

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/satishparmar)

</div>

---

## 📊 Profile Views

<div align="center">

![](https://komarev.com/ghpvc/?username=SatishParmar1&label=Profile%20Views&color=6C63FF&style=for-the-badge)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=150&section=footer&animation=fadeIn" width="100%"/>

### ✨ *"Code is like humor. When you have to explain it, it's bad."* – Cory House

**Made with ❤️ by Satish Parmar**

![Last Updated](https://img.shields.io/badge/Last%20Updated-February%202025-6C63FF?style=for-the-badge)

</div>
