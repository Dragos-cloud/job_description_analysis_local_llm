# Job Description Deep Analyzer
[https://www.orand-advisors.com/](https://www.orand-advisors.com/simple-tools/)

# A privacy-focused, offline AI tool for comprehensive job description analysis. Run powerful AI analysis entirely on your local machine using LM Studio - no data leaves your computer.
Get a deep analysis on the Job Description before you apply to better understand the requirements and to prepare for the interview.

## 🌟 Features

- **Complete Privacy**: All analysis runs locally on your machine via LM Studio
- **Comprehensive Analysis Modules**:
  - Core Competencies Breakdown (hard skills, soft skills, responsibilities)
  - Ideal Candidate Persona (psychological & professional profile)
  - Corporate Jargon Decoder (translate buzzwords to reality)
  - Red Flags & Culture Check (identify toxic traits and risks)
  - Interview Prep Generator (custom questions for the role)
  - Seniority & Market Positioning (salary estimates, career growth)
- **Clean, Modern UI**: Intuitive interface with tabbed navigation
- **Export Options**: Copy to clipboard or export as DOCX
- **User Guide**: Built-in carousel guide for setup and troubleshooting

## 🚀 Quick Start

### Prerequisites

1. **Install LM Studio** from [lmstudio.ai](https://lmstudio.ai)
2. Download a model (recommended: Llama 3 8B or similar)
3. Start the local server in LM Studio

### Usage

1. Open `standalone_jd_analysis_cm_user_guide_gemini.html` in your web browser
2. Click the refresh icon to connect to LM Studio
3. Select your model from the dropdown
4. Paste a job description
5. Select analysis modules (or keep defaults)
6. Click "Analyze Job Description"

## 📋 Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- LM Studio installed and running
- Sufficient RAM for your chosen AI model (typically 8GB+)

## 🔧 Configuration

The tool connects to LM Studio's default configuration:
- **Base URL**: `http://localhost:1234`
- **CORS**: Must be enabled in LM Studio settings

If you've changed the port in LM Studio, update the Base URL in the tool.

## 📖 Analysis Modules

### Core Competencies Breakdown
Detailed analysis of technical skills, soft skills, and day-to-day responsibilities ranked by importance.

### Ideal Candidate Persona
Goes beyond skills to profile the psychological and professional characteristics of the perfect hire.

### Corporate Jargon Decoder
Translates common buzzwords like "fast-paced" and "wear many hats" into actual workplace realities.

### Red Flags & Culture Check
Identifies warning signs including:
- Unrealistic requirements
- Poor work-life balance indicators
- Vague role definitions
- Includes a "Stress Score" estimate

### Interview Preparation
Generates role-specific questions:
- Technical/hard skill questions
- Behavioral questions (STAR method)
- Questions to ask the interviewer

### Seniority & Market Positioning
Estimates true seniority level, salary range, and career growth potential based on actual requirements.

## 🛠️ Troubleshooting

### "Disconnected" Status?
- Check if LM Studio's local server is running (green bar in "Local Server" tab)
- Ensure CORS is enabled in LM Studio's server settings
- Verify the port matches (default: 1234)

### Analysis Fails or Times Out?
- Try a smaller model if you're running low on memory
- Ensure the selected model is fully loaded in LM Studio
- Check LM Studio's console for error messages

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## ⚠️ Disclaimer

This tool provides analysis based on AI interpretation. Salary estimates and other predictions should be used as general guidance only. Always conduct your own research and due diligence when evaluating job opportunities.

## 🔒 Privacy

All analysis is performed locally on your machine. No data is sent to external servers or third parties. Your job descriptions and analysis results remain completely private.

---

Made with ❤️ for job seekers who value their privacy
