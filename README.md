Random forest combines the output of multiple decision trees to reach a single result. advanatage is it prevents overfitting and more accurate in predictions

Used load_iris from sklearn.datasets as my data

used np.random.unifor, (0,1,len(df)) <=.75           to seperate training and testing data randomly

used y = pd.factorize(train["species"]_)[0]          to make the species name input into digits.. since there are 3 type of flowers they will become 0,1,2

Print out confusion matrix at the end to visualize. We only missed two in total out of 40 and predicted the rest correctly.
