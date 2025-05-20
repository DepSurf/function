# Function: <code>set_buffer_delay</code>

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
In fs/ext4/inode.c (ffffffff8129715a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff8126e23c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff812c4783)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff81281476)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff812d9e33)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff8128ed2e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff812fdada)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff812b18ff)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813222ba)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff812d97a7)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff81351584)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff812eec94)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8136a3b0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/buffer.c (ffffffff813102ba)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8139372a)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8132328a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813ac0dc)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8135b990)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff813f84c5)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff81369f40)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff8140a168)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8136f0c0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff81410298)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff813bdd1d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff8146589e)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff814429e6)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff814e5267)
Location: include/linux/buffer_head.h:129
Inline: True
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
In fs/buffer.c (ffffffff814d19eb)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff8157e8ee)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff815080fb)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff815b26c6)
Location: include/linux/buffer_head.h:133
Inline: True
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
In fs/buffer.c (ffffffff8153ce5b)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/inode.c (ffffffff815eb561)
Location: include/linux/buffer_head.h:131
Inline: True
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
In fs/buffer.c (ffff8000103dc5e4)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffff80001047ebe0)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (c05b5a64)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (c063fa38)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (c0000000004e19ec)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (c0000000005a24f8)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffe000294918)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffe000309622)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8131b86a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813a46bc)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8130c40a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8139514c)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8131933a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813a1f1c)
Location: include/linux/buffer_head.h:130
Inline: True
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
In fs/buffer.c (ffffffff8132af78)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813b539c)
Location: include/linux/buffer_head.h:130
Inline: True
```
</details>
</li>
</ul>

## Differences
