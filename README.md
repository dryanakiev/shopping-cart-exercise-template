# shopping-cart-exercise

Write a ShoppingCart class that represents a shopping cart with the ability to add and remove items, as well as calculate the total cost of the items in the cart. The ShoppingCart class should have the following methods:

AddItem(string itemName, double price, int quantity): adds an item to the cart with the specified name, price, and quantity.
RemoveItem(string itemName): removes an item with the specified name from the cart.
GetTotalCost(): calculates and returns the total cost of the items in the cart.
Then, write unit tests to ensure that each of these methods is working correctly. Your tests should cover a range of scenarios, including:

1. Testing for correct addition of an item to the cart.
2. Testing for correct removal of an item from the cart.
3. Testing for correct calculation of the total cost of the items in the cart when the cart is empty.
4. Testing for correct calculation of the total cost of the items in the cart when there is only one item.
5. Testing for correct calculation of the total cost of the items in the cart when there are multiple items.

Here's a sample code structure to get you started:

```
public class ShoppingCart {
  // TODO: Implement the shopping cart class with appropriate methods and fields.
}

[TestFixture]
public class ShoppingCartTests {
  [Test]
  public void TestAddItem() {
    // TODO: Write test for adding an item to the cart
  }

  [Test]
  public void TestRemoveItem() {
    // TODO: Write test for removing an item from the cart
  }

  [Test]
  public void TestGetTotalCostEmptyCart() {
    // TODO: Write test for getting the total cost of an empty cart
  }

  [Test]
  public void TestGetTotalCostSingleItem() {
    // TODO: Write test for getting the total cost of a cart with a single item
  }

  [Test]
  public void TestGetTotalCostMultipleItems() {
    // TODO: Write test for getting the total cost of a cart with multiple items
  }
}
```

Your task is to complete the TODO comments with the appropriate code to implement the ShoppingCart class and its methods and write the unit tests to verify their correctness. Good luck!
