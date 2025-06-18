

# Career-_Consult 🧭

A bilingual career assessment tool that helps students discover their ideal career path based on their skills, interests, and personality.

![Career-_Consult Screenshot](screenshot.png) *Example screenshot - replace with your actual screenshot*

## Features ✨

- **20+ bilingual questions** (English + Bangla)
- **30+ career fields** across 6 domains:
  - Technology
  - Engineering
  - Medical/Healthcare
  - Business/Finance
  - Arts/Design
  - Sciences
- **Interactive assessment** with progress tracking
- **Personalized results** with top 3 career matches
- **Detailed career descriptions** with required skills
- **Beautiful UI** with animations and responsive design

## How It Works 🛠️

1. Users answer 20+ carefully designed questions
2. Each response adds weight to relevant career fields
3. System calculates best matches based on accumulated scores
4. Displays top 3 career recommendations with:
   - Match percentage
   - Field description
   - Required skills

## Technologies Used 💻

- **Frontend**: HTML5, CSS3, JavaScript
- **Animation**: GSAP (GreenSock Animation Platform)
- **Fonts**: Google Fonts (Poppins)
- **Design**: Custom CSS with modern gradients and transitions

## Installation 📥

No installation required! This is a client-side only application. Simply:

1. Download the `index.html` file
2. Open it in any modern web browser
3. Start your career discovery journey!

## Customization 🎨

To modify the application:

1. **Add more questions**:
   - Edit the `questions` array in the JavaScript section
   - Follow the existing format of bilingual questions and weights

2. **Add more career fields**:
   - Add to the `careerFields` object
   - Include corresponding descriptions in `careerDescriptions`

3. **Change styling**:
   - Modify the CSS variables in the `:root` selector
   - Adjust animations in the `@keyframes` sections

## Usage Example 💡

```javascript
// Sample question format
{
    question: "Question text in English / বাংলায় প্রশ্ন",
    options: [
        "Option 1 in English / বাংলায় বিকল্প ১",
        "Option 2 in English / বাংলায় বিকল্প ২",
        // ... more options
    ],
    weights: {
        "CareerField1": score,
        "CareerField2": score,
        // ... more fields
    }
}
