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