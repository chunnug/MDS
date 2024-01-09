## MDS
A multi-dimensional search is conducted to search for items by attributes. Each item here has three attributes, price, ID, and a list of descriptions. The key challenge addressed is efficiently searching through products based on these attributes.

## How It's Made
**Tech Used:** Java, Eclipse IDE

Various data structures are used, primarily hashing and reverse hashing techniques. The primary mapping connects the ID to the Item class. The secondary mapping connects each index of description to a tree set of items. The index is our key, and closed hashing is utilized to contain a set within each index. 

The following operations are supported

'Insert(id,price,list)': insert a new item whose description is given in the list

'Find(id)': return price of the item with a given id 

'Delete(id)': delete item from storage

'FindMinPrice(n)': given an integer, find items whose description contains that number and return the lowest price of those items

'FindMaxPrice(n)': given an integer, find items whose description contains that number and return the highest price of those items.

'FindPriceRange(n,low,high)': given int n, find the number of items whose description contains n and whose price falls between the given range

'RemoveNames(id, list)': Remove elements of the list from the description of the id

## Optimizations
 



