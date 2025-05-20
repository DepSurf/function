# Function: <code>get_empty_filp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8120e090)
Location: fs/file_table.c:103
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8120e090-ffffffff8120e241: get_empty_filp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81234ac0)
Location: fs/file_table.c:103
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81234ac0-ffffffff81234c71: get_empty_filp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81247670)
Location: fs/file_table.c:103
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81247670-ffffffff81247821: get_empty_filp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81252e80)
Location: fs/file_table.c:104
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81252e80-ffffffff81253030: get_empty_filp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81274f80)
Location: fs/file_table.c:104
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81274f80-ffffffff81275130: get_empty_filp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct file *get_empty_filp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:103
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8129bebb-ffffffff8129beef: get_empty_filp.cold.8 (STB_LOCAL)
ffffffff8129b840-ffffffff8129b9c0: get_empty_filp (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
