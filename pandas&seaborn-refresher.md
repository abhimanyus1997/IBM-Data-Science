# Misselenous pandas function
- `pd.groupby(by='COL_NAME', dropna=False).max/min/mean/std()`
- `pd.COL_NAME.unique()/nunique() `
	* gives unique elements and no of unique elements

# Pandas Multi-Indexing
- `pd.set_index() `
	* To create a MultiIndex with our original DataFrame, all we need to do is pass a list of columns into the .set_index()
	
# Seaborn - KDEplot (Kernel Density Estimate (KDE) Plot)
* allows us to estimate the probability density function of the continuous or non-parametric from our data set curve in one or more dimensions
- `sns.kdeplot(x,y)`

## Seaborn | Categorical Plots
- `sns.barplot(x='COL1', y='COL2', data=df)`
- `sns.countplot(x='COL1', data=df)`
- `sns.boxplot(x='COL1', y='COL2', data=df)`
- `sns.violenplot(x='COL1', y='COL2', data=df, split=True)`
	* Advanced boxplot with KDE distribution
- `sns.stripplot(x='COL1', y='COL2', data=df)`
	* Creates scatter plot based on category
- `sns.swarmplot(x='COL1', y='COL2', data=df)`
	* Creates scatter plot ON VIOLEN PLOT
- `sns.catplot`