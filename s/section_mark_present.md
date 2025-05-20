# Function: <code>section_mark_present</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void section_mark_present(struct mem_section *ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f5f7)
Location: mm/sparse.c:181
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff8121f5f7-ffffffff8121f651: section_mark_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8198f077)
Location: mm/sparse.c:177
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff819eb922)
Location: mm/sparse.c:177
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a26bdd)
Location: mm/sparse.c:178
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a9743e)
Location: mm/sparse.c:189
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81aced20)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void section_mark_present(struct mem_section *ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d172a)
Location: mm/sparse.c:190
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff812d172a-ffffffff812d1753: section_mark_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void section_mark_present(struct mem_section *ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81be8b26)
Location: mm/sparse.c:189
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81be8b26-ffffffff81be8b4f: section_mark_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void section_mark_present(struct mem_section *ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bdab52)
Location: mm/sparse.c:189
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
**Symbols:**

```
ffffffff81bdab52-ffffffff81bdab7b: section_mark_present (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff800010da0908)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000eed6f0)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe00001868e)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a6db90)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a2a0d7)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ad9fa0)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ae6456)
Location: mm/sparse.c:191
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:memory_present
```
</details>
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
</ul>
