# 📚 Class Bunk Calculator  

A simple yet powerful web tool to help students calculate how many lectures they can skip ("bunk") while maintaining their required attendance percentage.  

## 🚀 Features  

- ✅ **Quick Calculation** - Instantly know how many classes you can miss  
- 📱 **Responsive Design** - Works on desktop, tablet & mobile  
- 🎨 **Clean UI** - Intuitive interface with visual feedback  
- ⚠️ **Input Validation** - Prevents illogical inputs  
- 🟢🔴 **Color-Coded Results** - Green = safe to bunk, Red = need to attend  

## 🛠️ Built With  

- **Frontend**: Vanilla HTML, CSS, JavaScript  
- **Hosting**: GitHub Pages  


## 📖 How It Works  

1. Enter:  
   - Total classes this month  
   - Your institution's attendance criteria (%)  
   - Classes you've already attended  

2. Click "Calculate"  

3. Get instant results:  
   - "You can bunk X more classes" (green)  
   - OR "You need to attend X more classes" (red)  

## 🔍 The Math Behind It  

```javascript
minimumClassesRequired = Math.ceil((totalClasses * attendanceCriteria) / 100);
possibleBunks = attendedClasses - minimumClassesRequired;
```

## 🚀 Getting Started  

1. Clone the repo:  
   ```bash
   git clone https://github.com/ayushdogra25/bunker.git
   ```

2. Open `index.html` in your browser  

## 🤝 Contributing  

Found a bug or have an improvement? Open an issue or submit a PR!  

## 📜 License  

MIT © Ayush Dogra 

---  

💡 **Pro Tip:** Use this responsibly! Bunking too much might affect your learning 😉  

🌟 **Star this repo if you find it useful!**  
