# Function: <code>fuse_write_flags</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81429a04)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffff81476fd2)
Location: fs/fuse/file.c:1014
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write
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
In fs/fuse/file.c (ffffffff81491ddd)
Location: fs/fuse/file.c:1037
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write
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
In fs/fuse/file.c (ffffffff814995d8)
Location: fs/fuse/file.c:1032
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
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
In fs/fuse/file.c (ffffffff814f0e29)
Location: fs/fuse/file.c:1036
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
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
In fs/fuse/file.c (ffffffff815806ea)
Location: fs/fuse/file.c:1054
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff816232d0)
Location: fs/fuse/file.c:1054
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
```
**Symbols:**

```
ffffffff816232d0-ffffffff8162331d: fuse_write_flags.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8165b6b0)
Location: fs/fuse/file.c:1055
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
```
**Symbols:**

```
ffffffff8165b6b0-ffffffff8165b6fd: fuse_write_flags.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81695390)
Location: fs/fuse/file.c:1056
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write_pages
```
**Symbols:**

```
ffffffff81695390-ffffffff816953dd: fuse_write_flags.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffff80001050d968)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (c06c908c)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (c000000000654784)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffe000378726)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffff81421fe4)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffff81412a64)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffff8141e184)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
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
In fs/fuse/file.c (ffffffff81434ee4)
Location: fs/fuse/file.c:1041
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
</ul>

## Differences
