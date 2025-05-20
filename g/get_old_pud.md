# Function: <code>get_old_pud</code>

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
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812aaed0)
Location: mm/mremap.c:33
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812aaed0-ffffffff812ab038: get_old_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b0330)
Location: mm/mremap.c:32
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812b0330-ffffffff812b0480: get_old_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:33
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812f1b60-ffffffff812f1cc2: get_old_pud (STB_LOCAL)
ffffffff81cbcaa2-ffffffff81cbcabb: get_old_pud.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:33
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81355720-ffffffff81355882: get_old_pud (STB_LOCAL)
ffffffff81e6e627-ffffffff81e6e640: get_old_pud.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:35
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff813cfe90-ffffffff813cfff2: get_old_pud (STB_LOCAL)
ffffffff8206454c-ffffffff82064565: get_old_pud.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:35
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81404950-ffffffff81404ab5: get_old_pud (STB_LOCAL)
ffffffff820e3c27-ffffffff820e3c40: get_old_pud.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pud_t *get_old_pud(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mremap.c (0)
Location: mm/mremap.c:35
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81430f20-ffffffff81431085: get_old_pud (STB_LOCAL)
ffffffff821c07d0-ffffffff821c07e9: get_old_pud.cold (STB_LOCAL)
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
