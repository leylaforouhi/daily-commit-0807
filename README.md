def sort_numbers(numbers):
    return sorted(numbers)

if __name__ == "__main__":
    nums = [42, 7, 19, 3, 25, 10]
    print(f"Original list: {nums}")
    print(f"Sorted list: {sort_numbers(nums)}")
