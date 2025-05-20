# Function: <code>assoc_array_ptr_to_node</code>

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
In security/keys/keyring.c (ffffffff813311b3)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81404e09)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (ffffffff81365f4b)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8144e05f)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8137c76b)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8146ca1f)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_subtree_iterate
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
In security/keys/keyring.c (ffffffff8139038a)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81472134)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff813b58d0)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8149e887)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff813e628d)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814d3adf)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff81400a6f)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814e8442)
Location: include/linux/assoc_array_priv.h:148
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff8142d5fa)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81514dbe)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff8144734a)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815357fe)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff814988fa)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81599c93)
Location: include/linux/assoc_array_priv.h:144
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
In security/keys/keyring.c (ffffffff814b635d)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815b5699)
Location: include/linux/assoc_array_priv.h:144
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
In security/keys/keyring.c (ffffffff814bc1c0)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815c04c9)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
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
In security/keys/keyring.c (ffffffff81514aa0)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81627f51)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff815a7158)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff816f8b6c)
Location: include/linux/assoc_array_priv.h:144
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
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff81651148)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff817eb40c)
Location: include/linux/assoc_array_priv.h:144
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
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff81689a28)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8182b5a5)
Location: include/linux/assoc_array_priv.h:144
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
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff816c5f28)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8187d183)
Location: include/linux/assoc_array_priv.h:144
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
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffff800010530aa8)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffff800010641ffc)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (c06e8988)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c07e7a1c)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (c00000000067dc74)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c0000000007ecf24)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffe000391c6c)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffe00046e418)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff8143f92a)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8152ddde)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff8143039a)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8151e0be)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff8143baca)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81529e6e)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
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
In security/keys/keyring.c (ffffffff81452c1a)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8154384e)
Location: include/linux/assoc_array_priv.h:144
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_subtree_iterate
```
</details>
</li>
</ul>

## Differences
