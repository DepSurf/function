# Function: <code>split_huge_pages_in_file</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813000a0)
Location: mm/huge_memory.c:3060
Inline: False
```
**Symbols:**

```
ffffffff813000a0-ffffffff813002aa: split_huge_pages_in_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81349cf0)
Location: mm/huge_memory.c:3003
Inline: False
```
**Symbols:**

```
ffffffff81349cf0-ffffffff81349ef7: split_huge_pages_in_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813c05e0)
Location: mm/huge_memory.c:2971
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff813c05e0-ffffffff813c0923: split_huge_pages_in_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814430d0)
Location: mm/huge_memory.c:3069
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff814430d0-ffffffff81443258: split_huge_pages_in_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81478040)
Location: mm/huge_memory.c:3078
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff81478040-ffffffff814781cb: split_huge_pages_in_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int split_huge_pages_in_file(const char *file_path, long unsigned int off_start, long unsigned int off_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a7790)
Location: mm/huge_memory.c:3406
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff814a7790-ffffffff814a790f: split_huge_pages_in_file (STB_LOCAL)
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
