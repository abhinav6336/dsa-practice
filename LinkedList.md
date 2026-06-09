# Linked List Patterns & Important Points

## 1. Reversal Pattern (206)

Core Variables:

prev -> current -> next

Steps:

1. Save next
2. Reverse link
3. Move prev
4. Move current

Code Pattern:

next = current.next
current.next = prev
prev = current
current = next

---

## 2. Dummy Node Pattern

Purpose:
Handle head deletion/insertion without special cases.

Pattern:

dummy -> head

Return:
dummy.next

Used In:

* Merge Two Lists
* Remove Nth Node
* Many linked list questions

---

## 3. Tail Pointer Pattern

tail always points to the last node of the answer list.

Pattern:

tail.next = chosenNode
tail = tail.next

Used In:

* Merge Two Lists
* Build linked list questions

---

## 4. Fast & Slow Pointer Pattern

slow = 1 step
fast = 2 steps

Used In:

* Cycle Detection
* Find Middle
* Cycle Start

---

## 5. Cycle Detection (141)

If cycle exists:
fast eventually catches slow.

Pattern:

while(fast != null && fast.next != null)

If:
slow == fast

Cycle exists.

---

## 6. Find Middle Node (876)

slow = 1 step
fast = 2 steps

When:
fast reaches end

slow reaches middle.

---

## 7. Remove Duplicates Pattern (83)

Check:

current.val == current.next.val

If duplicate:

current.next = current.next.next

Else:

current = current.next

---

## 8. Two Pointer Gap Pattern (19)

Keep fast pointer n nodes ahead.

When fast reaches end:

slow is at required position.

---

## Common Mistakes

1. Forgetting null checks

while(fast != null && fast.next != null)

2. Losing links during reversal

Always save:

next = current.next

first.

3. Moving both pointers when only one should move

Example:
Merge Two Lists

4. Returning dummy instead of dummy.next

Wrong:
return dummy

Correct:
return dummy.next
