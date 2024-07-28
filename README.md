# Remove Linked List Elements

Problem
Remove all nodes from linked list that have the same value as the one given. After removing these nodes, return the new head of the modified linked list.

Solution
Input: 1 -> 2 -> 6 -> 3 -> 4 -> 5 -> 6.
Output: Given value is 6. Remove all occurrences of 6.

1. Create a “dummy” node at the beginning to handle edge cases (like removing the head node).
2. Traverse the linked list:
3. If the next node’s value equals 6, skip that node by updating the pointer.
4. Otherwise, move to the next node.
5. Finally, return the new head of the modified list (which is the node after the dummy node).
