# Function: <code>file_sample_sb_err</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e00a)
Location: include/linux/fs.h:2864
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff81315b8e)
Location: include/linux/fs.h:2864
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff8131a12a)
Location: include/linux/fs.h:2726
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff813210be)
Location: include/linux/fs.h:2726
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff8132020a)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff813274ae)
Location: include/linux/fs.h:2962
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff8136d7bd)
Location: include/linux/fs.h:2945
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff81374781)
Location: include/linux/fs.h:2945
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff813eb8c9)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff813f3b8b)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff81473c79)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8147c9db)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff814a846f)
Location: include/linux/pagemap.h:123
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814b1674)
Location: include/linux/pagemap.h:123
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
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
In fs/open.c (ffffffff814d954f)
Location: include/linux/pagemap.h:123
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2e44)
Location: include/linux/pagemap.h:123
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
