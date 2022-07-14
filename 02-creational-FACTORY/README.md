# Motivations
- Object creation logic becomes too convoluted
- Initializer is not descriptive
    - Name is always __init__
    - Cannot overload with same set of arguments with different names
    - can turn into 'optional parameter hell'
- Wholesale object creation (unlike builder) can be outsourced to:
    - A separate methos(Factory /method)
    - That may exist in a separate class (Factory)
    - can create hiararchy of factories with Abstarct Factory