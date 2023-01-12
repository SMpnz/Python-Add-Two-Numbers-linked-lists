# Add Two Numbers-linked lists
 You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list. You may assume the two numbers do not contain any leading zero, except the number 0 itself.

#### Example 1:
[![](https://mermaid.ink/img/pako:eNpFj8sKwjAQRX8lzMpAC-KjSheCWnGjG92oZDM0qS02icQUkdJ_N9Qp7uacOwNzW8itVJCCMEVt33mJzrPDSZi1CT4ZjSacszhesQ3xjHhLPOVcmIxgHsI-3ZFIBrH_nwtzIVgM6ZXEeBA3EkvOIQKtnMZKhi9bYRgT4EullYA0jBLdQ4Tvu7CHjbfnj8kh9a5RETRPiV5lFd4dakgLrF_BKll5646_2n377guYOExe?type=png)](https://mermaid.live/edit#pako:eNpFj8sKwjAQRX8lzMpAC-KjSheCWnGjG92oZDM0qS02icQUkdJ_N9Qp7uacOwNzW8itVJCCMEVt33mJzrPDSZi1CT4ZjSacszhesQ3xjHhLPOVcmIxgHsI-3ZFIBrH_nwtzIVgM6ZXEeBA3EkvOIQKtnMZKhi9bYRgT4EullYA0jBLdQ4Tvu7CHjbfnj8kh9a5RETRPiV5lFd4dakgLrF_BKll5646_2n377guYOExe)

```sh
Input: l1 = [2,4,3], l2 = [5,6,4]
Output: [7,0,8]
Explanation: 342 + 465 = 807.
```
#### Example 2:
```sh
Input: l1 = [0], l2 = [0]
Output: [0]
```
#### Example 3:
```sh
Input: l1 = [9,9,9,9,9,9,9], l2 = [9,9,9,9]
Output: [8,9,9,9,0,0,0,1]
```

## Constraints:
•	The number of nodes in each linked list is in the range [1, 100].
•	0 <= Node.val <= 9
•	It is guaranteed that the list represents a number that does not have leading zeros.
