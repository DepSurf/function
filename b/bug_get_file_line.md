# Function: <code>bug_get_file_line</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff815efd86)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff815efc60-ffffffff815efc71: bug_get_file_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8165ce96)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8165cd70-ffffffff8165cd81: bug_get_file_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81776298)
Location: lib/bug.c:129
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81776120-ffffffff8177613f: bug_get_file_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8201ec21)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8201ea50-ffffffff8201ea6f: bug_get_file_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8209ec31)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8209ea70-ffffffff8209ea8f: bug_get_file_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bug_get_file_line(struct bug_entry *bug, const char **file, unsigned int *line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff82176c31)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff82176a70-ffffffff82176a8f: bug_get_file_line (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
