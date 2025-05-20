# Function: <code>ext4_overwrite_io</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ext4_overwrite_io(struct inode *inode, loff_t pos, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812d4a90)
Location: fs/ext4/file.c:128
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff812d4a90-ffffffff812d4b25: ext4_overwrite_io (STB_LOCAL)
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
In fs/ext4/file.c (ffffffff812f1ccf)
Location: fs/ext4/file.c:135
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81316187)
Location: fs/ext4/file.c:138
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81344063)
Location: fs/ext4/file.c:138
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff8135c1c1)
Location: fs/ext4/file.c:138
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81385386)
Location: fs/ext4/file.c:138
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff8139de35)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff813e943d)
Location: fs/ext4/file.c:191
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_checks
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
In fs/ext4/file.c (ffffffff813fb7fd)
Location: fs/ext4/file.c:190
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_checks
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
In fs/ext4/file.c (ffffffff814020d3)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
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
In fs/ext4/file.c (ffffffff81454227)
Location: fs/ext4/file.c:189
Inline: True
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
In fs/ext4/file.c (ffffffff814d1938)
Location: fs/ext4/file.c:191
Inline: True
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
In fs/ext4/file.c (ffffffff8156a188)
Location: fs/ext4/file.c:206
Inline: True
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
In fs/ext4/file.c (ffffffff815a2049)
Location: fs/ext4/file.c:217
Inline: True
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
In fs/ext4/file.c (ffffffff815dad99)
Location: fs/ext4/file.c:217
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_checks
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
In fs/ext4/file.c (ffff800010471398)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (c0632140)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (c000000000591b58)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffe0002fd5a0)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81396415)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81386ea5)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81393d75)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff813a7e05)
Location: fs/ext4/file.c:139
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
