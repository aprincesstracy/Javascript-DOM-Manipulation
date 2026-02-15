 JavaScript DOM Manipulation

The DOM lets JavaScript interact with HTML elements to read, modify, or update content and styles.

🔹 Selecting Elements
document.getElementById("id")
document.querySelector(".class")
document.querySelectorAll("p")

🔹 Changing Content & Styles
element.textContent = "New Text"
element.innerHTML = "<em>HTML</em>"
element.style.color = "blue"

🔹 Adding & Removing Elements
let li = document.createElement("li")
parent.appendChild(li)
parent.removeChild(child)

🔹 Event Handling
button.addEventListener("click", () => alert("Clicked!"))