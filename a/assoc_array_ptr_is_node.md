# Function: <code>assoc_array_ptr_is_node</code>

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
Location: include/linux/assoc_array_priv.h:131
Inline: True
```
```
In lib/assoc_array.c (ffffffff81404f96)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_destroy_subtree
  - lib/assoc_array.c:assoc_array_apply_edit
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
Location: include/linux/assoc_array_priv.h:131
Inline: True
```
```
In lib/assoc_array.c (ffffffff8144cfed)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_destroy_subtree
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
Location: include/linux/assoc_array_priv.h:131
Inline: True
```
```
In lib/assoc_array.c (ffffffff8146b9ad)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_destroy_subtree
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
Location: include/linux/assoc_array_priv.h:131
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/assoc_array_priv.h:131
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
Location: include/linux/assoc_array_priv.h:131
Inline: True
```
```
In lib/assoc_array.c (0)
Location: include/linux/assoc_array_priv.h:131
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
In security/keys/keyring.c (ffffffff813e6271)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814d31dc)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff81400a52)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff814e7b3c)
Location: include/linux/assoc_array_priv.h:131
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff8142d5de)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8151449c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff8144732e)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81534edc)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff81498a30)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8159960c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff814b6494)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815b501c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff814bc2ef)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff815bfe4c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
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
In security/keys/keyring.c (ffffffff81514c46)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8162780f)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (ffffffff815a7354)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff816f83af)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (ffffffff81651344)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff817eac1f)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (ffffffff81689c19)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8182ad9f)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (ffffffff816c6119)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8187c86f)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_walk
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
In security/keys/keyring.c (ffff800010530a90)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffff80001064180c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (c06e896c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c07e721c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (c00000000067dc4c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (c0000000007ec2ac)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffe000391c58)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffe00046dd50)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff8143f90e)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8152d4bc)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff8143037e)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8151d79c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff8143baae)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff8152954c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
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
In security/keys/keyring.c (ffffffff81452bfe)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - security/keys/keyring.c:search_nested_keyrings
```
```
In lib/assoc_array.c (ffffffff81542f2c)
Location: include/linux/assoc_array_priv.h:127
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_cancel_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert_into_terminal_node
```
</details>
</li>
</ul>

## Differences
