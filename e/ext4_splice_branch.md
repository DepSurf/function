# Function: <code>ext4_splice_branch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d93fb)
Location: fs/ext4/indirect.c:412
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813091b8)
Location: fs/ext4/indirect.c:412
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131f1c8)
Location: fs/ext4/indirect.c:412
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f80e3)
Location: fs/ext4/indirect.c:412
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131c727)
Location: fs/ext4/indirect.c:413
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8134a737)
Location: fs/ext4/indirect.c:413
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813628e9)
Location: fs/ext4/indirect.c:413
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138b7ee)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a423e)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_splice_branch(handle_t *handle, struct ext4_allocation_request *ar, Indirect *where, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ef610)
Location: fs/ext4/indirect.c:417
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813ef610-ffffffff813ef74a: ext4_splice_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_splice_branch(handle_t *handle, struct ext4_allocation_request *ar, Indirect *where, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81401d60)
Location: fs/ext4/indirect.c:417
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81401d60-ffffffff81401e9a: ext4_splice_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81408e8d)
Location: fs/ext4/indirect.c:417
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145b902)
Location: fs/ext4/indirect.c:418
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d9766)
Location: fs/ext4/indirect.c:418
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81572568)
Location: fs/ext4/indirect.c:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815aa303)
Location: fs/ext4/indirect.c:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e30a3)
Location: fs/ext4/indirect.c:425
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff800010477b38)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0639354)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c00000000059a094)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe000302c72)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139c81e)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138d2ae)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139a07e)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ae567)
Location: fs/ext4/indirect.c:407
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
