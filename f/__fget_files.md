# Function: <code>__fget_files</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *__fget_files(struct files_struct *files, unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813387f0)
Location: fs/file.c:717
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff813387f0-ffffffff81338862: __fget_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *__fget_files(struct files_struct *files, unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344180)
Location: fs/file.c:817
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff81344180-ffffffff81344209: __fget_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *__fget_files(struct files_struct *files, unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a520)
Location: fs/file.c:829
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff8134a520-ffffffff8134a5a9: __fget_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *__fget_files(struct files_struct *files, unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398290)
Location: fs/file.c:900
Inline: False
Direct callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff81398290-ffffffff81398345: __fget_files (STB_LOCAL)
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
In fs/file.c (ffffffff8141af14)
Location: fs/file.c:908
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814a6e9a)
Location: fs/file.c:908
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814dbe7a)
Location: fs/file.c:909
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff8150edb2)
Location: fs/file.c:1031
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:fget_task
  - fs/file.c:fget
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
