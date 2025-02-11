# SafeScan - AI-Powered Healthcare Access

## Overview
Health Oracle is an AI-driven application designed to empower individuals with timely access to healthcare. The platform provides self-service health assessments, AI-based medical analysis, and seamless doctor appointment booking, reducing delays and improving diagnostics.

## Problem Statement
Millions lack timely, affordable healthcare access, leading to delayed diagnoses and poor health outcomes. The current system is specialist-dependent, causing bottlenecks and information asymmetry, preventing preventive care and informed decision-making.

## Solution
Health Oracle offers:
- **AI-Powered Medical Analysis:** Users upload CT/MRI scans to receive AI-driven insights.
- **Self-Service Health Assessments:** AI models predict potential abnormalities and suggest treatments.
- **AI Medical Assistant:** Provides instant clarification and healthcare guidance.
- **Doctor Appointment Booking:** Direct connection to relevant specialists.
- **Email Notifications:** Automated appointment confirmation via EmailJS.

## System Architecture
1. **User uploads medical documents** via the SafeScan App.
2. **Document scanning and text extraction** occurs.
3. **Azure Custom Vision predicts diseases** based on dataset comparison.
4. **Doctor database fetches relevant specialists** based on AI analysis.
5. **Chatbot (GPT-3.5-turbo/Gemini Pro) assists users** with queries.
6. **Results are displayed and appointments booked** as needed.
7. **Email notifications are sent** to users and doctors.

  ![image](https://github.com/user-attachments/assets/7798f905-f56f-495e-8025-1e30128bdfae)

- **Deployment:** Streamlit Cloud
- **AI & ML:** Microsoft Azure AI Custom Vision
- **Automation:** Microsoft Azure Logic App
- **Chatbot:** Cloudflare AI Workflow
- **Database:** Kintone (Doctor’s Data Storage & Retrieval)
- **Email Integration:** EmailJS
- **Text Editing:** TinyMCE (Under Development)
- **Version Control & Hosting:** GitHub, GitHub Codespaces

## How to Use
1. **Upload Medical Scans** - CT or MRI.
2. **AI Analysis** - Get instant results.
3. **Consult Chatbot** - Ask medical queries.
4. **Book an Appointment** - Schedule a consultation.
5. **Receive Email Notification** - Confirm your appointment.

## Future Enhancements
- Expansion to detect more medical conditions.
- Improved chatbot responses with multimodal AI.
- Integration with telemedicine platforms.

## Contributing
1. Fork the repository.
2. Create a feature branch.
3. Commit changes.
4. Submit a pull request.

## License
MIT License

---
Health Oracle - Revolutionizing Access & Diagnosis for All

