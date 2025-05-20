# Function: <code>assoc_array_ptr_is_shortcut</code>

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
Location: include/linux/assoc_array_priv.h:127
Inline: True
```
```
In lib/assoc_array.c (ffffffff81404e8a)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_gc
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
Location: include/linux/assoc_array_priv.h:127
Inline: True
```
```
In lib/assoc_array.c (ffffffff8144df31)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
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
Location: include/linux/assoc_array_priv.h:127
Inline: True
```
```
In lib/assoc_array.c (ffffffff8146c8f1)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
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
Location: include/linux/assoc_array_priv.h:127
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/assoc_array_priv.h:127
Inline: True
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
Location: include/linux/assoc_array_priv.h:127
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/assoc_array_priv.h:127
Inline: True
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
In security/keys/keyring.c (ffffffff813e60c4)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814d3b22)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff81400894)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814e8485)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8142d428)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81514e01)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff81447178)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81535841)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff81498872)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81599cd6)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff814b62e2)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815b56dc)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff814bc142)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815c050c)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff815149fe)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81627fa1)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff815a70bb)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff816f8bc2)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff816510ab)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff817eb462)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8168998b)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8182b5fb)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff816c5e8b)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8187d1d9)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffff800010530928)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffff800010642038)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (c06e87d0)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c07e7a5c)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_walk
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (c00000000067d998)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c0000000007ecd14)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffe000391ac8)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffe00046e43e)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8143f758)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8152de21)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff814301c8)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8151e101)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8143b8f8)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81529eb1)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff81452a48)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81543891)
Location: include/linux/assoc_array_priv.h:123
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
</ul>

## Differences
