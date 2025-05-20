# Function: <code>assoc_array_ptr_to_shortcut</code>

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
In security/keys/keyring.c (ffffffff813311a1)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81404e01)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_subtree_iterate
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (ffffffff81365f39)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8144e057)
Location: include/linux/assoc_array_priv.h:153
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
In security/keys/keyring.c (ffffffff8137c759)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8146ca17)
Location: include/linux/assoc_array_priv.h:153
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
In security/keys/keyring.c (ffffffff8139037b)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814722f4)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (ffffffff813b58c1)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8149ea47)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:153
Inline: True
```
```
In lib/assoc_array.c (ffffffff814d3c79)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:153
Inline: True
```
```
In lib/assoc_array.c (ffffffff814e85ef)
Location: include/linux/assoc_array_priv.h:153
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff81514f54)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff81535994)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (ffffffff81498881)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81599c93)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff814b62f1)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815b5699)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff814bc151)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815c04c9)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff81514a0d)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81627f51)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff815a70ca)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff816f89f0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff816510ba)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff817eb290)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff8168999a)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8182b424)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (ffffffff816c5e9a)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8187cfd3)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_apply_edit
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffff80001064218c)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (c07e7bfc)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (c0000000007ece9c)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffe00046e554)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff8152df74)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff8151e254)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff8152a004)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
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
In security/keys/keyring.c (0)
Location: include/linux/assoc_array_priv.h:149
Inline: True
```
```
In lib/assoc_array.c (ffffffff815439e4)
Location: include/linux/assoc_array_priv.h:149
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
```
</details>
</li>
</ul>

## Differences
