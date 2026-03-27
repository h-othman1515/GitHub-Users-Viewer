# 🌌 GitHub Users Viewer

> Fetching data from the GitHub API and displaying users dynamically using vanilla JavaScript.

---

## 📌 Module

**Working with Data & APIs** — JavaScript Internship Curriculum
Orange Digital Village · Coding School

---

## 🎯 Objective

Fetch real data from the GitHub API and render it dynamically inside the DOM — no hardcoded content, no libraries, just JavaScript.

---

## 🌐 API Endpoint

```
https://api.github.com/users
```

### 🔑 Keys Used from Response

| Key | Description |
|---|---|
| `login` | Username |
| `avatar_url` | Profile image |
| `html_url` | GitHub profile link |

---

## 💻 Requirements

- ✅ Use `fetch()` to get data from the API
- ✅ Convert the response to JSON using `.json()`
- ✅ Loop through the array of users
- ✅ Display each user inside a card (image + username + profile link)
- ✅ Show a loading message while data is being fetched
- ✅ Handle errors with `.catch()`
- ✅ All data comes from the API — nothing is hardcoded

---

## ⚡ Bonus

- ✅ Show only the first **10 users** using `.slice(0, 10)`
- ✅ Hover effect on cards
- ✅ Profile link opens in a **new tab**
- ✅ Grid layout using CSS

---

## 🧠 Concepts Covered

### JSON
| Operation | Method | Description |
|---|---|---|
| Decode | `JSON.parse()` | JSON String → Object |
| Encode | `JSON.stringify()` | Object → JSON String |

### fetch() Chain
```js
fetch(url)
  .then(function(res) { return res.json(); })
  .then(function(data) { /* use data */ })
  .catch(function(err) { /* handle error */ });
```

### HTTP Methods
| Method | Use |
|---|---|
| `GET` | Retrieve data from API |
| `POST` | Send data to API |

### Status Codes
| Code | Meaning |
|---|---|
| `200` | ✅ Success |
| `404` | ❌ Not Found |
| `500` | ❌ Server Error |

---

## 🗂️ File Structure

```
📁 working-with-data-apis/
├── 📄 github-users-viewer.html
├── 🖼️ GitHub_Invertocat_Black.svg
└── 📄 README.md
```

---

## 🚀 How to Run

1. Clone or download the repository
2. Make sure `github-users-viewer.html` and `GitHub_Invertocat_Black.svg` are in the **same folder**
3. Open `github-users-viewer.html` in your browser
4. Users will load automatically from the GitHub API

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- Vanilla JavaScript — no frameworks, no libraries
- `fetch()` API for HTTP requests
- DOM manipulation with `createElement` & `appendChild`
- CSS Grid for layout

---
