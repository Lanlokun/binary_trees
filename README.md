# 0x1D. C - Binary trees


# 0. New node

    Write a function that creates a binary tree node
<ul>
        gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 0-main.c 0-binary_tree_node.c -o 0-node
        ./0-node
</ul>



# 1. Insert left

    Write a function that inserts a node as the left-child of another node

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 1-main.c 1-binary_tree_insert_left.c 0-binary_tree_node.c -o 1-left        
    ./1-left
</ul>

# 2. Insert right


    Write a function that inserts a node as the right-child of another node



<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 2-main.c 2-binary_tree_insert_right.c 0-binary_tree_node.c -o 2-right
    ./2-right   
</ul>

# 3. Delete


    Write a function that deletes an entire binary tree

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 3-main.c 3-binary_tree_delete.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 3-del
    ./3-del
</ul>

# 4. Is leaf


    Write a function that checks if a node is a leaf


<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 4-binary_tree_is_leaf.c 4-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 4-leaf
    ./4-leaf
</ul>

# 5. Is root


    Write a function that checks if a given node is a root

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 5-binary_tree_is_root.c 5-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 5-root    
    ./5-root
</ul>

# 6. Pre-order traversal


    Write a function that goes through a binary tree using pre-order traversal

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 6-main.c 6-binary_tree_preorder.c 0-binary_tree_node.c -o 6-pre  
    ./6-pre
</ul>

# 7. In-order traversal

    Write a function that goes through a binary tree using in-order traversal

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 7-main.c 7-binary_tree_inorder.c 0-binary_tree_node.c -o 7-in
    ./7-in
</ul>

# 8. Post-order traversal

    Write a function that goes through a binary tree using post-order traversal

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 8-main.c 8-binary_tree_postorder.c 0-binary_tree_node.c -o 8-post
    ./8-post
</ul>


# 9. Height


    Write a function that measures the height of a binary tree

<ul>
   gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 9-binary_tree_height.c 9-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 9-height
    ./9-height
</ul>

# 10. Depth


    Write a function that measures the depth of a node in a binary tree

<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 10-binary_tree_depth.c 10-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 10-depth
    ./10-depth
</ul>

# 11. Size

    Write a function that measures the size of a binary tree

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 11-binary_tree_size.c 11-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 11-size
    ./11-size

</ul>

# 12. Leaves


    Write a function that counts the leaves in a binary tree


<ul>
    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 12-binary_tree_leaves.c 12-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 12-leaves
    ./12-leaves

</ul>

# 13. Nodes

    Write a function that counts the nodes with at least 1 child in a binary tree


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 13-binary_tree_nodes.c 13-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 13-nodes
    ./13-nodes

</ul>

# 14. Balance factor


    Write a function that measures the balance factor of a binary tree


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 14-binary_tree_balance.c 14-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c 1-binary_tree_insert_left.c -o 14-balance
    ./14-balance

</ul>

# 15. Is full


    Write a function that checks if a binary tree is full


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 15-binary_tree_is_full.c 15-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 15-full
    ./15-full

</ul>

# 16. Is perfect

    Write a function that checks if a binary tree is perfect

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 16-binary_tree_is_perfect.c 16-main.c 0-binary_tree_node.c 2-binary_tree_insert_right.c -o 16-perfect
    ./16-perfect

</ul>

# 17. Sibling

    Write a function that finds the sibling of a node


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 17-main.c 17-binary_tree_sibling.c 0-binary_tree_node.c -o 17-sibling
    ./17-sibling
    
</ul>

# 18. Uncle

    Write a function that finds the uncle of a node


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 18-main.c 18-binary_tree_uncle.c 0-binary_tree_node.c -o 18-uncle
    ./10-uncle

</ul>


# 19. Lowest common ancestor

    Write a function that finds the lowest common ancestor of two nodes

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 100-main.c 100-binary_trees_ancestor.c 0-binary_tree_node.c -o 100-ancestor
    ./100-ancestor

</ul>

# 20. Level-order traversal


    Write a function that goes through a binary tree using level-order traversal

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 101-main.c 101-binary_tree_levelorder.c 0-binary_tree_node.c 3-binary_tree_delete.c -o 101-lvl
    ./101-lvl

 </ul>

 # 21. Is complete


    Write a function that checks if a binary tree is complete

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 102-main.c 102-binary_tree_is_complete.c 0-binary_tree_node.c 3-binary_tree_delete.c -o 102-complete
    ./102-complete

</ul>

# 22. Rotate left


    Write a function that performs a left-rotation on a binary tree


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 103-binary_tree_rotate_left.c 103-main.c 0-binary_tree_node.c -o 103-rotl
    ./103-rotl

</ul>

# 23. Rotate right


    Write a function that performs a right-rotation on a binary tree

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 104-binary_tree_rotate_right.c 104-main.c 0-binary_tree_node.c -o 104-rotr
    ./104-rotr

</ul>

# 24. Is BST


    Write a function that checks if a binary tree is a valid Binary Search Tree

<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 111-bst_insert.c 111-main.c 0-binary_tree_node.c -o 111-bst_insert
    ./111-bst_insert

</ul>

# 25. BST - Insert


    Write a function that inserts a value in a Binary Search Tree

<ul>

     gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 111-bst_insert.c 111-main.c 0-binary_tree_node.c -o 111-bst_insert
     ./111-bst_insert

</ul>

# 26. BST - Array to BST


    Write a function that builds a Binary Search Tree from an array


<ul>

    gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c 112-array_to_bst.c 112-main.c 111-bst_insert.c 0-binary_tree_node.c -o 112-bst_array
    ./112-bst_array

</ul>

# 27. BST - Search


    Write a function that searches for a value in a Binary Search Tree














