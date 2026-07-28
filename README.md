# Car Price Prediction

Otomobil özelliklerine göre satış fiyatı tahmini yapan regression projesi. Kaggle Automobile Market Analytics dataseti kullanıldı.

## Dataset
- ~7,500 araç, 15 özellik
- Target: Selling_price (sürekli sayı)
- Kaynak: [Kaggle - Automobile Market Analytics](https://www.kaggle.com/datasets/deeplumiere/automobile-market-analytics-dataset)

## Yaklaşım
1. EDA + görselleştirme (marka, model, fiyat dağılımı)
2. Missing values: kategorik → mode, sayısal → mean/median
3. Feature engineering + Model kolonunu drop
4. Encoding: Ordinal (Service_History), Binary (Transmission), One-Hot (Body_Type, Fuel_Type, Color, Make, Location vs.)
5. StandardScaler
6. Train/test split (80/20)
7. 3 model karşılaştırması
