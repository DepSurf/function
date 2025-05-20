# Function: <code>find_mm_struct</code>

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
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ed010)
Location: mm/migrate.c:1910
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812ed010-ffffffff812ed2e8: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f33b0)
Location: mm/migrate.c:1893
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812f33b0-ffffffff812f3684: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133d820)
Location: mm/migrate.c:1961
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8133d820-ffffffff8133daf4: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b0ad0)
Location: mm/migrate.c:1899
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff813b0ad0-ffffffff813b0db9: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81431620)
Location: mm/migrate.c:2015
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81431620-ffffffff81431909: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81467060)
Location: mm/migrate.c:2349
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81467060-ffffffff8146734c: find_mm_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *find_mm_struct(pid_t pid, nodemask_t *mem_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814962a0)
Location: mm/migrate.c:2375
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814962a0-ffffffff8149658c: find_mm_struct (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
