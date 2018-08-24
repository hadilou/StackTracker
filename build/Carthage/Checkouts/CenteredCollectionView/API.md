## CenteredCollectionViewFlowLayout API
You can use all properties inherited from `UICollectionViewFlowLayout`.

**CenteredCollectionViewFlowLayout specific properties**:

* **`currentCenteredPage`** calculates the current centered page
  ```Swift
  var currentCenteredPage: Int? { get }
  ```

* **`scrollDirection`** direction of scrolling **(supports vertical)**
  ```Swift
  var scrollDirection: UICollectionViewScrollDirection { get set }
  // default: .horizontal
  ```

* **`scrollTo(index: animated:)`** programmatically scrolls to a cell at a specified index.
  ```Swift
  func scrollTo(index: Int, animated: Bool)
  ```
