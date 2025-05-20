# Function: <code>dquot_reserve_block</code>

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
In fs/ext4/inode.c (ffffffff8129703e)
Location: include/linux/quotaops.h:336
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents.c (ffffffff812c9582)
Location: include/linux/quotaops.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/inode.c (ffffffff812c4672)
Location: include/linux/quotaops.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents.c (ffffffff812f84f4)
Location: include/linux/quotaops.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/inode.c (ffffffff812d9d22)
Location: include/linux/quotaops.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents.c (ffffffff8130e4bd)
Location: include/linux/quotaops.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff812ed406)
Location: include/linux/quotaops.h:344
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
```
In fs/ext4/inode.c (ffffffff812fdc29)
Location: include/linux/quotaops.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents.c (ffffffff81311ecd)
Location: include/linux/quotaops.h:340
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81322409)
Location: include/linux/quotaops.h:340
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents.c (ffffffff8133fd9c)
Location: include/linux/quotaops.h:343
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813514b2)
Location: include/linux/quotaops.h:343
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/inode.c (ffffffff8136a07e)
Location: include/linux/quotaops.h:343
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff813934ee)
Location: include/linux/quotaops.h:343
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff813abe9e)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f81ee)
Location: include/linux/quotaops.h:355
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409e8e)
Location: include/linux/quotaops.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff8141005e)
Location: include/linux/quotaops.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff814631b1)
Location: include/linux/quotaops.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff814e0df1)
Location: include/linux/quotaops.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff8157a3b1)
Location: include/linux/quotaops.h:355
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff815b1f41)
Location: include/linux/quotaops.h:355
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff815ead71)
Location: include/linux/quotaops.h:354
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffff80001047e94c)
Location: include/linux/quotaops.h:353
Inline: True
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
In fs/ext4/inode.c (c063e864)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (c0000000005a0a40)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffe0003093ac)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff813a447e)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff81394f0e)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff813a1cde)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
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
In fs/ext4/inode.c (ffffffff813b389e)
Location: include/linux/quotaops.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
```
</details>
</li>
</ul>

## Differences
