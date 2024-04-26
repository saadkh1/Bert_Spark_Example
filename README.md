# Spark For Sentiment Analysis With Bert

![1](images/spark_nlp.png)

This notebook demonstrates sentiment analysis for restaurant review data in both English and Arabic using pre-trained BERT models with Spark NLP and PySpark.

## Getting Started

This repository requires Apache Spark and Spark NLP to be installed. Refer to the official Spark NLP documentation for installation instructions: [Spark NLP Documentation](https://www.johnsnowlabs.com/spark-nlp/)


## Sentiment Analysis of English Restaurant Reviews with BERT (Example)

| opinion                                                                                              | sentiment |
|-----------------------------------------------------------------------------------------------------|-----------|
| Highly recommend the restaurant for its tasty dishes and cozy atmosphere                             | Positive  |
| We ordered takeout, and the packaging was eco-friendly. Appreciated the sustainability effort        | Positive  |
| Great ambiance and friendly staff. The menu has a variety of options to choose from                  | Positive  |
| The staff was attentive, and they ensured our dietary preferences were taken into account            | Positive  |
| We tried the chef's specials, and they were a delightful surprise. Unique and delicious              | Positive  |
| The cocktails were overpriced, considering the size and alcohol content                              | Negative  |
| The menu had a good balance of classic dishes and innovative creations                               | Positive  |
| The staff was attentive to details, ensuring our preferences were taken into account                 | Positive  |
| Unfortunately, the restaurant had a limited selection of non-alcoholic beverages. More variety needed| Negative  |
| The cocktails were well-crafted and paired perfectly with the appetizers                             | Positive  |


## Sentiment Analysis of Arabic Restaurant Reviews with BERT (Example)

| opinion                                                                                         | sentiment |
|------------------------------------------------------------------------------------------------|-----------|
| كانت تجربة الطعام مخيبة للآمال بالكامل، حيث كانت الأطباق تفتقر إلى الطعم اللذيذ والنضارة اللازمة| negative  |
| كان للمطعم ديكور فريد وساحر. مكان عظيم لمناسبة خاصة                                             | positive  |
| كان للمطعم جو دافئ وترحاب. مثالية لعشاء مريح                                                    | positive  |
| المطعم كان جيدًا للقاءات العادية، لكنه قد لا يكون الخيار الأمثل للمناسبات الخاصة                | neutral   |
| الطعام كان لذيذ حقا! مزيج مثالي من النكهات والقوام                                              | positive  |
| كانت الأطعمة عادية والخدمة مقبولة، لم نشعر بإحباط كبير أو إثارة كبيرة                           | neutral   |
| لم نجد أي تجربة سلبية أو إيجابية بارزة، كانت الزيارة مجردة مناسبة                               | neutral   |
| كان للمطعم ديكور فريد وساحر. مكان عظيم لمناسبة خاصة                                             | positive  |
| لقد شعرنا بخيبة أمل إزاء نوعية الطعام. أنها تفتقر إلى النكهة والنضارة                           | negative  |
| كانت الأطعمة عادية والخدمة مقبولة، لم نشعر بإحباط كبير أو إثارة كبيرة                           | neutral   |
| المطعم كان جيدًا للقاءات العادية، لكنه قد لا يكون الخيار الأمثل للمناسبات الخاصة                | neutral   |
| لم نجد أي مشكلة كبيرة في تجربتنا، كانت معقولة بشكل عام                                          | neutral   |
| أوصي بشدة بالمطعم لأطباقه اللذيذة وأجواءه المريحة                                               | positive  |
| تجربتنا في المطعم كانت متوسطة. لم تكن الأطعمة رائعة ولكنها لم تكن سيئة أيضًا                    | neutral   |
| كانت الأطعمة عادية والخدمة مقبولة، لم نشعر بإحباط كبير أو إثارة كبيرة                           | neutral   |
| الأطعمة كانت عديمة الطعم والجودة. كان ذلك خيبة أمل بالنسبة لنا ولم يستحق الزيارة                | negative  |
| لقد شعرنا بخيبة أمل إزاء نوعية الطعام. أنها تفتقر إلى النكهة والنضارة                           | negative  |
| كان للمطعم جو دافئ وترحاب. مثالية لعشاء مريح                                                    | positive  |
| كانت الخدمة في المطعم مقبولة، لم يكن هناك شيء ملحوظًا سواء إيجابيًا أو سلبيًا                   | neutral   |


**For more details and an end-to-end stream pipeline project, please contact me via email at [saadkhemiri123@gmail.com](mailto:saadkhemiri123@gmail.com).**
![2](images/image2.jpg)
