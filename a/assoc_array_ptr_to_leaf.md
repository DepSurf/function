# Function: <code>assoc_array_ptr_to_leaf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:136
Inline: True
```
```
In lib/assoc_array.c (ffffffff8140528c)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:136
Inline: True
```
```
In lib/assoc_array.c (ffffffff8144e251)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:136
Inline: True
```
```
In lib/assoc_array.c (ffffffff8146cc11)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:136
Inline: True
```
```
In lib/assoc_array.c (ffffffff814720b8)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:136
Inline: True
```
```
In lib/assoc_array.c (ffffffff8149e808)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e5895)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff814d3a58)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400075)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff814e83bb)
Location: include/linux/assoc_array_priv.h:136
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142c835)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff81514d37)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81446585)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff81535777)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81498295)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff81599c0e)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b5d05)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff815b561c)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bbb85)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff815c044c)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815143e5)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff81627ec0)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a69f5)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff816f8ae1)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81650975)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff817eb381)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81689255)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff8182b51a)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c5715)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff8187d0f8)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff80001052f7f4)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffff800010641f78)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e7a5c)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (c07e79ac)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067c5d8)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (c0000000007ecc60)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000391012)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffe00046e3c0)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143eb65)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff8152dd57)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142f5d5)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff8151e037)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143ad05)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff81529de7)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81451e55)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_check_iterator
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_detect_cycle_iterator
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_diff_objects
  - security/keys/keyring.c:keyring_compare_object
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
```
In lib/assoc_array.c (ffffffff815437c7)
Location: include/linux/assoc_array_priv.h:132
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_find
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
</ul>

## Differences
