DSA

Built in functions time complexities:

list.append(), dict (get,set) - O(1)
to use `in` in set for conditions - O(1)

list.insert() - O(n)
to use `in` in list for conditions - O(n)
 

Hashmap Working:

When a key and a value is passed to a hashmap, a index is calculated using hash(key). At this particular index, the value passed is stored. So, whenever a key retrieval is tried, it just hashes finds the index and directly returns the value irrespective of size of the array.

But a rare problem that may occur is same hash for two keys. In this scenario, using linear probing it finds the nearest address available and allocates the value.


Two Pointers: 

Using two indexes to solve the problem ((slow and fast)

When to use two pointers? Some keywords to identify:

- pair sum
- target sum
- closest sum
- remove duplicates


Two types of Two Pointer Patterns:

1. Opposite Direction:

Used for: Pair sum, Palindrome, Container with most water, Trapping rain water

If the problem mentions a sorted array and asks about pairs, triplets, or a target sum, immediately think of opposite-direction two pointers.

General Algorithm:

left = 0
right = len(arr)-1

while left < right:

    if condition:
        return result

    elif need_larger:
        left += 1

    else:
        right -= 1


2. Same Direction:

Used for: Remove duplicates, Move zeros, Linked list cycle detection, Sliding transformations

General Algorithm:

slow = 0

for fast in range(len(arr)):
    if condition(arr[fast]):
        arr[slow] = arr[fast]
        slow += 1


3. Fast and Slow for Cycle Detection:

   used mostly in linked lists. slow moves 1, fast moves 2. If cycle exists, fast meets slow.


filter() is one of the fast and nice python util

