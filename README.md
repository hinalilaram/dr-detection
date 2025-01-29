
# Automated Detection of Diabetic Retinopathy using Smartphone-Based Photography 👁️🤖  
*A cost-effective AI solution for early DR screening in underserved communities*  

## 📌 Overview  
This project leverages **deep learning** and smartphone photography to detect diabetic retinopathy (DR), a leading cause of blindness in diabetics. By integrating a 200 Diopter lens with a smartphone camera, we capture fundus images and classify them using a **VGG16 model** (74.5% validation accuracy) deployed on a mobile app. Designed for rural areas with limited access to ophthalmologists, this system aims to democratize early DR diagnosis.  

## 🚀 Key Features  
- **Low-Cost Device**: Uses a 200 Diopter lens + smartphone for fundus imaging.  
- **AI-Powered Classification**: Compares VGG16, ResNet50, and Custom CNN models.  
- **Mobile Integration**: Deploys the best-performing model on an Android app.  
- **Scalable**: Targets regions with <1 ophthalmologist per 100,000 people.  

## 🔍 Motivation  
- **35-75%** of diabetics develop DR, but 80% of Pakistan’s ophthalmologists work in urban areas.  
- Traditional fundus cameras cost **$10,000+**; our solution is **100x cheaper**.  
- Early detection can prevent blindness in **90% of cases** (WHO).  

## 🛠️ Technical Architecture  
1. **Image Acquisition**: Smartphone + 20D lens.  
2. **Preprocessing**: Resizing, normalization, augmentation.  
3. **Model Training**:  
   - **VGG16** (74.5% validation accuracy)  
   - **ResNet50** (74.1% validation accuracy)  
   - **Custom CNN** (74.1% validation accuracy)  
4. **Mobile Deployment**: Android app for real-time classification.  

## 📊 Dataset & Results  
- **Dataset**: 200 fundus images (DR vs. No-DR).  
- **Performance**:  

| Model          | Validation Accuracy | Validation Loss |
|----------------|---------------------|-----------------|
| VGG16          | 74.53%              | 0.5594          |
| ResNet50       | 74.08%              | 0.5872          |
| Custom CNN     | 74.05%              | 0.5726          |  


🤝 Contributors
- Hina Liaram
- Sarmad Talpur
- Sharjeel Memon
- Irfan Ali Bhacho

For collaboration contact me here:
📧 `hinalilaram@gmail.com` 