<h2>🩺 Deep4ORL — Deep Learning for Otoscopy in Low-Resource Settings</h2>


<h5> Intro </h5>
Deep4ORL is a deep learning project designed to improve the automated diagnosis of ear pathologies from otoscopy images, with a focus on clinical environments in low-resource settings. The project enhances an existing AlexNet-based model, expands the training dataset, and deploys the improved model in real-world healthcare facilities for validation.


<h5>Context</h5>

Otoscopy—the visual examination of the tympanic membrane—is essential for diagnosing common ear infections such as otitis. However, correct interpretation of otoscopic images requires specialist expertise often unavailable in rural or low-resource regions. This project aims to close that gap by developing a robust, clinically validated AI model capable of assisting front-line healthcare workers.

Many primary healthcare facilities in low-income regions lack trained ENT specialists, leading to misdiagnosis, late interventions, and antibiotic misuse. Existing AI diagnostic tools are costly, closed-source, and not adapted to local image quality or prevalent diseases.

Deep4ORL upgrades an existing AlexNet model into a more accurate, robust, and deployable diagnostic tool

- Model Improvement: Fine-tune and optimize the AlexNet architecture for multi-class classification (12 ear pathologies).
- Clinical Validation: Deploy and test the improved model in real-world healthcare settings

📊 <h5>Dataset</h5>
The dataset includes:
New otoscopy images collected across multiple clinical sites, anonymized and annotated by ENT specialists
Balanced across 12 targeted pathologies, augmented to increase model robustness. The dataset is also subjected to Terms of Service and Privacy Policy of the owner



<h5> Deployment & Use Cases</h5>
The Deep4ORL model is designed for integration into Telemedicine platforms, a digital health mobile apps (e.g., KORAI)
The model provides:
- Automatic diagnosis
- Heatmaps for visual explainability
- Integration through REST API
