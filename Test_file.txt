import pytest

# content of test_addition.py

def add_numbers(a, b):
    return a + b

def test_add_numbers():
    # Arrange
    a = 3
    b = 5
    expected_result = 8

    # Act
    result = add_numbers(a, b)

    # Assert
    assert result == expected_result, f"Expected {expected_result}, got {result}"
