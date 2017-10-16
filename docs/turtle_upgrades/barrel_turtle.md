# Barrel Turtle

The Barrel Turtle Upgrade is an upgrade which allows turtles to get barrel storage (storing 64 stacks of any one item).

## Functions
| Function | Returns | Description |
|----------|---------|-------------|
|get([_number_ amount])|_number_ numberOfItems|This function retrieves either the given amount or a stack of the item and puts it in the selected slot|
|put([_number_ amount])|_number_ numberOfItems|This function puts either the given amount or a stack of the selected item into the barrel inventory|
|getUnlocalizedName()|_string_ unlocalizedName|Returns the unlocalized name of the item stored|
|getLocalizedName()|_string_ name|Returns the localized name of the item stored|
|getItemID()|_string_ resource_location|Returns the item id of the item stored|
|getAmount()|_number_ amount|Returns the amount of the item stored|
|getOreDictEntries()|_table_ entries|Returns the OreDictionary entries for the stored item|