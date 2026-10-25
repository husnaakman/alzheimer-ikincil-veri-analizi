# Alzheimer Hastalığında Demografik ve Bilişsel Faktörlerin İkincil Veri Analizi

Hüsna Akman - 361526087
Araştırma Yöntem ve Teknikleri dersi proje çalışması

## Problem ve Amaç

Alzheimer, yaşlılarda en sık görülen nörolojik hastalıklardan biridir ve yaşlı nüfus arttıkça daha fazla insanı etkilemektedir. Yapılan çalışmalar yaş ve eğitim düzeyi gibi bazı faktörlerin Alzheimer ile ilişkili olduğunu göstermektedir. Bu projede açık erişimli bir veri seti kullanarak Alzheimer tanısı olan ve olmayan kişileri yaş, cinsiyet, eğitim, sosyoekonomik durum ve bilişsel test puanı açısından karşılaştırmayı amaçlıyorum.

Araştırma sorusu: Alzheimer tanısı olan ve olmayan bireyler yaş, cinsiyet, eğitim, sosyoekonomik durum ve MMSE puanı bakımından farklılık gösteriyor mu?

## Literatür



Kaynaklar:
- Battineni, G., Chintalapudi, N., & Amenta, F. (2019). Machine learning in medicine: Performance calculation of dementia prediction by support vector machines (SVM). Informatics in Medicine Unlocked, 16, 100200. https://doi.org/10.1016/j.imu.2019.100200
- Livingston, G., Huntley, J., Liu, K. Y., vd. (2024). Dementia prevention, intervention, and care: 2024 report of the Lancet standing Commission. The Lancet, 404(10452), 572-628. https://doi.org/10.1016/S0140-6736(24)01296-0
- Marcus, D. S., Fotenos, A. F., Csernansky, J. G., Morris, J. C., & Buckner, R. L. (2010). Open Access Series of Imaging Studies (OASIS): Longitudinal MRI data in nondemented and demented older adults. Journal of Cognitive Neuroscience, 22(12), 2677-2684. https://doi.org/10.1162/jocn.2009.21407
- Stern, Y. (2012). Cognitive reserve in ageing and Alzheimer's disease. The Lancet Neurology, 11(11), 1006-1012. https://doi.org/10.1016/S1474-4422(12)70191-6

## Veri Seti

OASIS-2 veri setini kullanacağım. Washington Üniversitesi tarafından hazırlanmış ve ücretsiz olarak paylaşılmış bir veri seti. Veri setinde hasta grubu “Demented” olarak adlandırılmıştır ve bu gruptaki bireyler çok hafif veya hafif düzeyde Alzheimer tanısı almıştır.
- Kaggle: https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers
- Asıl kaynak: https://sites.wustl.edu/oasisbrains/home/oasis-2
- Değişkenler: grup (hasta / sağlıklı / sonradan hastalık gelişen), yaş, cinsiyet, eğitim yılı, sosyoekonomik durum, MMSE, CDR



## Yöntem ve Hipotezler

Analizleri Google Colab'da Python ile yapmayı planlıyorum. Çalışma ilerledikçe yöntem değişebilir.

Hipotezler:
- H1: Alzheimer tanılı bireylerin eğitim yılı ortalaması daha düşüktür.
- H2: Alzheimer tanılı bireylerin yaş ortalaması daha yüksek, MMSE puanı daha düşüktür.
- H3: Eğitim yılı ile MMSE puanı arasında pozitif bir ilişki vardır.

## Sonraki Adımlar

- Veri setini indirip depoya eklemek
- Makaleleri daha detaylı okumak
