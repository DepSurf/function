# Function: <code>replace_mm_exe_file</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int replace_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3270)
Location: kernel/fork.c:1212
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
**Symbols:**

```
ffffffff810b3270-ffffffff810b3407: replace_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int replace_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9490)
Location: kernel/fork.c:1284
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
**Symbols:**

```
ffffffff810c9490-ffffffff810c9632: replace_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int replace_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e69c0)
Location: kernel/fork.c:1305
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
**Symbols:**

```
ffffffff810e69c0-ffffffff810e6ba6: replace_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int replace_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2360)
Location: kernel/fork.c:1446
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
**Symbols:**

```
ffffffff810f2360-ffffffff810f2566: replace_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int replace_mm_exe_file(struct mm_struct *mm, struct file *new_exe_file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fbf20)
Location: kernel/fork.c:1443
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
**Symbols:**

```
ffffffff810fbf20-ffffffff810fc14f: replace_mm_exe_file (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
