# Function: <code>ext4_has_feature_sparse_super2</code>

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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1691
Inline: True
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1759
Inline: True
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1744
Inline: True
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1749
Inline: True
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1709
Inline: True
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
In fs/ext4/balloc.c (ffffffff8133629d)
Location: fs/ext4/ext4.h:1712
Inline: True
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
In fs/ext4/balloc.c (ffffffff8134d51d)
Location: fs/ext4/ext4.h:1725
Inline: True
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
In fs/ext4/balloc.c (ffffffff81375f1d)
Location: fs/ext4/ext4.h:1745
Inline: True
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
In fs/ext4/balloc.c (ffffffff8138e18d)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffff813d96ad)
Location: fs/ext4/ext4.h:1897
Inline: True
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
In fs/ext4/balloc.c (ffffffff813eb35d)
Location: fs/ext4/ext4.h:2021
Inline: True
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
In fs/ext4/balloc.c (ffffffff813f1890)
Location: fs/ext4/ext4.h:2030
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
In fs/ext4/balloc.c (ffffffff814438e0)
Location: fs/ext4/ext4.h:2095
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8148aa3c)
Location: fs/ext4/ext4.h:2095
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_begin
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
In fs/ext4/balloc.c (ffffffff814bf77f)
Location: fs/ext4/ext4.h:2097
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8150d2c0)
Location: fs/ext4/ext4.h:2097
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_list_backups
  - fs/ext4/resize.c:ext4_resize_begin
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
In fs/ext4/balloc.c (ffffffff8155770f)
Location: fs/ext4/ext4.h:2107
Inline: True
```
```
In fs/ext4/resize.c (ffffffff815a8020)
Location: fs/ext4/ext4.h:2107
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_list_backups
  - fs/ext4/resize.c:ext4_resize_begin
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
In fs/ext4/balloc.c (ffffffff8158f52f)
Location: fs/ext4/ext4.h:2101
Inline: True
```
```
In fs/ext4/resize.c (ffffffff815de8a0)
Location: fs/ext4/ext4.h:2101
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_list_backups
  - fs/ext4/resize.c:ext4_resize_begin
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
In fs/ext4/balloc.c (ffffffff815c823f)
Location: fs/ext4/ext4.h:2119
Inline: True
```
```
In fs/ext4/resize.c (ffffffff81617350)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_list_backups
  - fs/ext4/resize.c:ext4_resize_begin
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
In fs/ext4/balloc.c (ffff800010460300)
Location: fs/ext4/ext4.h:1801
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
In fs/ext4/balloc.c (c0620b28)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (c00000000057c778)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffe0002ef936)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffff8138676d)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffff813771fd)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffff8138423d)
Location: fs/ext4/ext4.h:1801
Inline: True
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
In fs/ext4/balloc.c (ffffffff81397dbd)
Location: fs/ext4/ext4.h:1801
Inline: True
```
</details>
</li>
</ul>

## Differences
