Project Overview:
Machine learning regression model untuk memprediksi median harga rumah di California berdasarkan data sensus tahun 1990. Project ini menggunakan Linear Regression dengan comprehensive data preprocessing dan exploratory data analysis untuk membangun model prediksi yang dapat membantu stakeholder real estate dalam proses valuasi properti.

Business Context:
Perusahaan real estate, investor properti, dan perencana kota menghadapi tantangan dalam menentukan harga rumah yang akurat berdasarkan karakteristik lokasi dan properti. Proses valuasi manual membutuhkan waktu lama dan seringkali menghasilkan estimasi yang tidak konsisten, yang dapat menyebabkan kerugian finansial dan menghambat efisiensi proses jual-beli properti.

 Data Source: [Link](https://drive.google.com/file/d/1PGLl2kmI17BVQtpxFBmmVTSFABSAIZA9/view?usp=sharing)
### Features Description

| Feature | Type | Description |
|---------|------|-------------|
| `longitude` | Float | Longitude coordinates (-124.35 to -114.31) |
| `latitude` | Float | Latitude coordinates (32.54 to 41.95) |
| `housing_median_age` | Integer | Median age of houses in the district (1-52 years) |
| `total_rooms` | Integer | Total number of rooms in the district |
| `total_bedrooms` | Integer | Total number of bedrooms in the district |
| `population` | Integer | Total population in the district |
| `households` | Integer | Total number of households in the district |
| `median_income` | Float | Median income of households (in $10k USD) |
| `ocean_proximity` | Categorical | Proximity to ocean (NEAR BAY, <1H OCEAN, INLAND, NEAR OCEAN, ISLAND) |
| `median_house_value` | Float | **Target Variable** - Median house value in USD |
