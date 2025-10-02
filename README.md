// ═══════════════════════════════════════════════════
//     Connect. Automate. Forget.
// ═══════════════════════════════════════════════════

const person = {
  firstName: "Ivan",
  middleName: "Hristov",
  lastName: "Kostadinov",
  email: "nbukostadinov@gmail.com",
  
  techStack: [
    "Java", 
    "JavaScript", 
    "Python",
    "HTML/CSS",
    "APIs", 
    "AI Tools & LLMs"
  ],
  
  education: [
    { institution: "SoftUni", course: "Fundamentals", status: "✓ Completed" },
    { institution: "SoftUni", course: "Java Advanced", status: "✓ Completed" },
    { institution: "SoftUni", course: "JS Front End", status: "✓ Completed" },
    { institution: "Vibe Coding", course: "AI Development", status: "✓ Completed" },
    { institution: "Online", course: "Prompt Engineering", status: "✓ Completed" },
    { institution: "Online", course: "AI Automation", status: "✓ Completed" }
  ],
  
  hobbies: ["🎣 Fishing", "🎮 PC Games", "🎬 Cinema"],
  
  currentMission: () => {
    return `Looking for like-minded people to build a team and dive deep 
            into the world of AI-powered automation and optimization. 
            Let's create tools that work while we sleep! 🚀`;
  },
  
  philosophy: "Connect. Automate. Forget."
};

console.log(person.currentMission());
// Output: "Ready to automate the future? Let's connect! 💡"
