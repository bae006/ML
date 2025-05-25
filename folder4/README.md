Описание проекта

Проект представляет собой анализ данных о дрожжах для бинарной классификации (классы: negative и positive). Основная цель — построить и сравнить модели классификации на основе дерева решений, случайного леса и метода опорных векторов (SVM), оптимизировать их гиперпараметры и оценить производительность. Проект включает этапы загрузки и предобработки данных, разделения выборки, подбора гиперпараметров с помощью GridSearchCV, оценки моделей по метрикам (Accuracy, Precision, Recall, F1-score, ROC-AUC) и визуализации ROC-кривой.

Использованные библиотеки
1) numpy, pandas - обработка данных
2) matplotlib - визуализация
3) sklearn.model_selection - для разделения данных на обучающую и тестовую выборки (train_test_split) и подбора гиперпараметров (GridSearchCV).
4) sklearn.tree - для построения модели дерева решений (DecisionTreeClassifier) и визуализации дерева (plot_tree).
5) sklearn.ensemble - для построения модели случайного леса (RandomForestClassifier).
6) sklearn.svm - для построения модели метода опорных векторов (SVC).
7) sklearn.metrics - для вычисления метрик оценки (Accuracy, Precision, Recall, F1-score, ROC-AUC) и построения ROC-кривой (RocCurveDisplay, roc_curve, roc_auc_score, classification_report, confusion_matrix).
