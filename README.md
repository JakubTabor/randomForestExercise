# randomForestExercise
# First i load my iris data """iris = load_iris()"""
# Then i set them my df. into columns """pd.DataFrame(iris.data, columns=iris.feature_names)"""
# I create column "target" """df['target'] = iris.target"""
# Then i split my all data and separate my "target" column from rest of data 
# Next i get my "RandomForestClassifier" and train """model.fit(X_train,Y_train)""" 
# Get "score" and tray to set number of "trees" at (40) so my n_estimators" """RandomForestClassifier(n_estimators=40)"""
