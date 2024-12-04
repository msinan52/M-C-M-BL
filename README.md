# M-C&M-BL: A Novel Classification Model For Brain Tumor Classification: Multi-CNN And Multi-BiLSTM

  The human brain is the most important organ that distinguishes humans from other creatures. Any unhealthy condition of the human brain affects the normal flow of life. Diseases such as brain tumors disrupt all activities of daily life. The first procedure for brain tumors is surgery, which is detected by developing imaging technologies. In this paper, we propose a new method for tumor classification on stable and publicly available reliable Br35H open source brain magnetic resonance imaging (MRI) data. The proposed model (M-C&M-BL) is a combination of the Convolutional Neural Network (CNN), which is a widely used approach in image classification, and the Bi-directional Long Short Term Memory (BiLSTM), which is employed in text classification. To assess the method, the following performance metrics were employed: Accuracy (Acc), F1 score (F1), Precision (Pre), Recall (Rec), Specificity (Spe), and Matthews correlation coefficient (MCC). Temel ölçütlere göre değerlendirilen model, %99,33 Doğruluk ve %99,35 F1 puanı elde ederek BMRI-Net (%98,33 Doğruluk ve %98,33 F1 puanı) ve AlexNet (%98,79 Doğruluk ve %98,82 F1 puanı) gibi CNN tabanlı modellerden daha iyi performans göstermiştir. Ayrıca, %99,67 ile biraz daha yüksek bir doğruluk oranı bildiren MobileNetv2 ile karşılaştırıldığında da rekabetçi sonuçlar ortaya koymuştur.
 The proposed approach has significant potential for real-world medical applications, such as integration into clinical decision support systems, web or mobile-based diagnostic platforms and hospital PACS systems. These applications can assist healthcare professionals in early diagnosis, improve accuracy and reduce diagnostic time. However, challenges such as ensuring privacy, generalisability across diverse datasets and overcoming infrastructure limitations need to be addressed for seamless deployment. By demonstrating the feasibility of combining different deep learning architectures, this study lays the foundation for AI-driven tools that can improve clinical workflows and patient outcomes.


tüm kod sayfaları aşağıdaki gibidir
1Bilstm.ipynb
1CNN.ipynb
3CNN.ipynb
3Bİlstm.ipynb
3CNN-3Bilstm.ipynb (M-C&M-BL)
