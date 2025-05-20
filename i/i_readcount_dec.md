# Function: <code>i_readcount_dec</code>

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
In fs/file_table.c (ffffffff8120e5cf)
Location: include/linux/fs.h:2531
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81234ff2)
Location: include/linux/fs.h:2646
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81247b9f)
Location: include/linux/fs.h:2615
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812533cf)
Location: include/linux/fs.h:2740
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812754d2)
Location: include/linux/fs.h:2801
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff8129bd78)
Location: include/linux/fs.h:2823
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812b0a3a)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812cd3bf)
Location: include/linux/fs.h:2900
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812deddf)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81315eef)
Location: include/linux/fs.h:3004
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81321479)
Location: include/linux/fs.h:2839
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81327219)
Location: include/linux/fs.h:3092
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff81374aec)
Location: include/linux/fs.h:3080
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff813f38e3)
Location: include/linux/fs.h:2846
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/open.c (ffffffff81473f87)
Location: include/linux/fs.h:3000
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8147c6bf)
Location: include/linux/fs.h:3000
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/open.c (ffffffff814a87d3)
Location: include/linux/fs.h:2614
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814b1243)
Location: include/linux/fs.h:2614
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/open.c (ffffffff814d98c3)
Location: include/linux/fs.h:2898
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2ab8)
Location: include/linux/fs.h:2898
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffff8000103855b4)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (c056e398)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (c00000000047b40c)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffe000258234)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812d73bf)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812c803f)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812d51cf)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
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
In fs/file_table.c (ffffffff812e6015)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
</details>
</li>
</ul>

## Differences
