# Function: <code>pick_file</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813443b0)
Location: fs/file.c:599
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff813443b0-ffffffff81344439: pick_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a750)
Location: fs/file.c:599
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff8134a750-ffffffff8134a7d9: pick_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813984f0)
Location: fs/file.c:609
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff813984f0-ffffffff81398584: pick_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141bef6)
Location: fs/file.c:637
Inline: True
Inline callers:
  - fs/file.c:__close_fd_get_file
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:close_fd_get_file
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff8141a720-ffffffff8141a795: pick_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6be0)
Location: fs/file.c:637
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff814a6be0-ffffffff814a6c55: pick_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *pick_file(struct files_struct *files, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dbbb0)
Location: fs/file.c:637
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_range
```
**Symbols:**

```
ffffffff814dbbb0-ffffffff814dbc34: pick_file (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
