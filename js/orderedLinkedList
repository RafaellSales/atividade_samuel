
class OrderedLinkedList extends LinkedList {
  constructor() {
    super()
  }

  insertOrdered(element) {
    if (super.isEmpty()) {
      super.append(element)
    } else {
      for (let index = 0; index < super.size(); index++) {
        if (super.getElement(index) > element) {
          super.insert(index, element)
          return
        } else if (index == super.size() - 1) {
          super.append(element)
          return
        }
      }
    }
  }

  append(element) {
    this.insertOrdered(element)
  }
}
