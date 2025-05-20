# Function: <code>fat_ioctl_fitrim</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813c5e27)
Location: fs/fat/file.c:124
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff813f0dfc)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff8140acdc)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_ioctl_fitrim(struct inode *inode, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81457af0)
Location: fs/fat/file.c:125
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81457af0-ffffffff81457bd0: fat_ioctl_fitrim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_ioctl_fitrim(struct inode *inode, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81473e40)
Location: fs/fat/file.c:125
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81473e40-ffffffff81473f1d: fat_ioctl_fitrim (STB_LOCAL)
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
In fs/fat/file.c (ffffffff8147a6dd)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff814d1d4d)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff8155ea6e)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff81600c6e)
Location: fs/fat/file.c:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff81638b61)
Location: fs/fat/file.c:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff81672051)
Location: fs/fat/file.c:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffff8000104eb32c)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (c06a90f8)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (c00000000062960c)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffe00035ba74)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff814032bc)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff813f3d3c)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff8140063c)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
In fs/fat/file.c (ffffffff8141626c)
Location: fs/fat/file.c:125
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
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
