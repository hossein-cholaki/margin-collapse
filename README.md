# margin-collapse
Collapsing margins happen when two vertical margins come in contact with one another.
If one margin is greater than the other, then that margin overrides the other, leaving one margin.
when both margins are positive, the bigger margin will be total vertical margin.
If one of the margin be positive and another be negative then The margin between two elements decreases
If both margins are negative, the margin that collapses is the bigger negative of those two.
If both margin are equal, One of the margins collapses

When two elements have a parent-child relationship, the child margin will be overridden by their parent margin. and if we adding 1px of padding, than we can use both of them.
The same would be true if we added border-top to the parent. As long as something solid sits between the parent and child, both margins will be used.

the margins of floating and absolutely positioned elements never collapse.

If there is no border, padding, inline content, height, or min-height to separate an empty block's margin-top from its margin-bottom, then its top and bottom margins collapse.
