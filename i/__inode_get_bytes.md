# Function: <code>__inode_get_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8127887e)
Location: include/linux/fs.h:3079
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff812e7552)
Location: include/linux/fs.h:3079
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812a059e)
Location: include/linux/fs.h:3100
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff813132d2)
Location: include/linux/fs.h:3100
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812b557e)
Location: include/linux/fs.h:3175
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff8132a262)
Location: include/linux/fs.h:3175
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812d232e)
Location: include/linux/fs.h:3186
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81351e32)
Location: include/linux/fs.h:3186
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812e3ebe)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff8136a1b2)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff8131b17e)
Location: include/linux/fs.h:3309
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff813b2388)
Location: include/linux/fs.h:3309
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff8132654e)
Location: include/linux/fs.h:3109
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff813c3968)
Location: include/linux/fs.h:3109
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff8132c65e)
Location: include/linux/fs.h:3362
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff813ca632)
Location: include/linux/fs.h:3362
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff81379dce)
Location: include/linux/fs.h:3344
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff8141b103)
Location: include/linux/fs.h:3344
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff813f7f90)
Location: include/linux/fs.h:3122
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81493967)
Location: include/linux/fs.h:3122
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff814813f0)
Location: include/linux/fs.h:3276
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81527637)
Location: include/linux/fs.h:3276
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff814b6020)
Location: include/linux/fs.h:2891
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff8155fb14)
Location: include/linux/fs.h:2891
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff814e8330)
Location: include/linux/fs.h:3172
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81596204)
Location: include/linux/fs.h:3172
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffff80001038aa08)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffff800010432e94)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (c0572520)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (c05fc654)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (c000000000482d70)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (c0000000005469d0)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffe00025cbc2)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffe0002ce800)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812dc49e)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81362792)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812cd11e)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81353432)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812da2ae)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81360262)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
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
In fs/stat.c (ffffffff812e9d70)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
```
```
In fs/quota/dquot.c (ffffffff81374490)
Location: include/linux/fs.h:3248
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
```
</details>
</li>
</ul>

## Differences
