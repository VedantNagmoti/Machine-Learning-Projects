## One-hot encoding 
is a method used in multi-class classification to represent categorical target variables as numerical vectors. 
This is necessary because most machine learning algorithms cannot directly process categorical data.
How One-Hot Encoding Works for Multi-Class Classification:
* Identify Unique Classes: Determine all the distinct categories or classes present in the target variable. For example, if classifying animal types, the classes might be "cat," "dog," and "bird."
* Create Binary Columns: For each unique class, a new binary column is created. Each of these new columns will represent one specific class.
* Assign Binary Values: For each data instance, the column corresponding to its actual class is assigned a value of 1, while all other newly created class columns are assigned a value of 0.
