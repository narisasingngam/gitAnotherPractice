# How to write code productively

1. Always using descriptive name
    ```python
      # This is not good
      def a():
        return "AAAAA"
        return "a"
    ```
1. Always write good document
    ```python
    def add(a, b):
    """
    Add two numbers together.

    :return: sum of two number
    :raise: ypeError when arguments are not number
    """
    if type(a) != int or type(b) != int:
      raise TypeError
    return a + b
    ```
1. Implement superunittest
1. Use Agile Development Process
1. Use Scrum