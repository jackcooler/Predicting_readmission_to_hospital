PL version below
# Predicting_readmission_to_hospital

This project deals with the problem of predicting readmissions to a health care facility (hospital). The dataset used in the project contains a number of columns containing various information about the condition of patients and medical records. The "readmitted" column contains information whether the patient was readmitted to hospital in less than 30 days, after more than 30 days or  was not readmitted to hospital.

The aim of the project is to create a model that, based on patient data, will effectively predict whether such a person will be hospitalized in less than 30 days after leaving the hospital, longer than 30 days or not.

In the project there were used KNN, decision tree and random forest classifier models. The dataset was not balanced at the beginning and required processing. The quantitative imbalance in the column containing information about the readmission of the patient was of great importance here and it was the reason why the SMOTE balancing method was used. The results before and after using this method are respectively presented in the project. The notebook will be further developed.

# Przewidywanie_ponownych_przyjęć_do_szpitala

Niniejszy projekt ten dotyczy problemu przewidywania ponownego przyjęcia do placówki opieki zdrowotnej (rehospitalizacji). Zbiór danych wykorzystany w projekcie zawiera szereg kolumn zawierających różne informacje o stanie pacjentów i dokumentacji medycznej. W rubryce „readmitted” znajduje się informacja, czy pacjent został ponownie przyjęty do szpitala w okresie krótszym niż 30 dni, po więcej niż 30 dniach lub nie został ponownie przyjęty do szpitala.

Celem projektu jest stworzenie modelu, który na podstawie danych pacjenta będzie skutecznie przewidywał, czy taka osoba będzie rehospitalizowana w mniej niż 30 dni po opuszczeniu szpitala, więcej niż 30 dni, czy też nie.

W projekcie wykorzystano modele KNN (algorytm najbliższych sąsiadów), drzewa decyzyjnego i Random Forest Classifier. Zbiór danych nie był na początku zrównoważony i wymagał przetworzenia danych. Ogromne znaczenie miało tutaj niezbalansowanie ilościowe w kolumnie zawierającej informacje o rehospitalizacji pacjenta i dlatego zastosowano metodę balansowania SMOTE. W projekcie przedstawiono odpowiednio wyniki przed i po zastosowaniu tej metody. Notatnik będzie dalej rozwijany.

