# pandas-challenge
Module 4 Challenge


Sources I used while writting my code:
    
    https://stackoverflow.com/questions/29765548/remove-index-name-in-pandas
        To delete index name
            Input [19] : .rename_axis(None)

    https://stackoverflow.com/questions/32464280/how-to-convert-currency-column-with-and-to-numbers
        To undo currency formatting on ‘Per Student Budget’ column in order to use pd.cut 
            Input [26] : .replace('[\$,]', '', regex=True).astype(float)

Personal Notes:

    I feel like I did a lot of pd.merge in this code:
    If there is another way I could have created the dataframes by combining the multiple DFs/Series I would be intersted to know how. 
    Overall this was an intersting and challenging assignment.
