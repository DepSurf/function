# Function: <code>migrate_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e149f)
Location: mm/mempolicy.c:953
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ffe8f)
Location: mm/mempolicy.c:985
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120f580)
Location: mm/mempolicy.c:987
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff8120f580-ffffffff8120f665: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121b730)
Location: mm/mempolicy.c:915
Inline: False
```
**Symbols:**

```
ffffffff8121b730-ffffffff8121b815: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81236a30)
Location: mm/mempolicy.c:969
Inline: False
```
**Symbols:**

```
ffffffff81236a30-ffffffff81236b15: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259a00)
Location: mm/mempolicy.c:945
Inline: False
```
**Symbols:**

```
ffffffff81259a00-ffffffff81259ae5: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d760)
Location: mm/mempolicy.c:985
Inline: False
```
**Symbols:**

```
ffffffff8126d760-ffffffff8126d845: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81289010)
Location: mm/mempolicy.c:1023
Inline: False
```
**Symbols:**

```
ffffffff81289010-ffffffff812890f4: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81298b80)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81298b80-ffffffff81298c8d: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ccd10)
Location: mm/mempolicy.c:1093
Inline: False
```
**Symbols:**

```
ffffffff812ccd10-ffffffff812cce2e: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d85a0)
Location: mm/mempolicy.c:1071
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff812d85a0-ffffffff812d86ee: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dfbd0)
Location: mm/mempolicy.c:1081
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff812dfbd0-ffffffff812dfd1e: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326fe0)
Location: mm/mempolicy.c:1052
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff81326fe0-ffffffff81327131: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81395e70)
Location: mm/mempolicy.c:1048
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff81395e70-ffffffff81395fd1: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814158d0)
Location: mm/mempolicy.c:1062
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff814158d0-ffffffff81415a3c: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814490b0)
Location: mm/mempolicy.c:1068
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff814490b0-ffffffff8144921f: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81482a80)
Location: mm/mempolicy.c:1018
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff81482a80-ffffffff81482c16: migrate_to_node (STB_LOCAL)
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
In mm/mempolicy.c (ffff8000103376f8)
Location: mm/mempolicy.c:1024
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412330)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
c000000000412330-c000000000412488: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291160)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81291160-ffffffff8129126d: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81282de0)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
ffffffff81282de0-ffffffff81282eed: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ef70)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
ffffffff8128ef70-ffffffff8128f07d: migrate_to_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_to_node(struct mm_struct *mm, int source, int dest, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129ee70)
Location: mm/mempolicy.c:1024
Inline: False
```
**Symbols:**

```
ffffffff8129ee70-ffffffff8129ef7d: migrate_to_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
