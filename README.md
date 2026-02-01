# 34.-Unique-words-from-comma-separated-input-sorted-
items = input("Input comma separated sequence of words: ")

words = items.split(",")

print(",".join(sorted(set(words))))
