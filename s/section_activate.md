# Function: <code>section_activate</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a972fb)
Location: mm/sparse.c:780
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff81acebdd)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bc74d9)
Location: mm/sparse.c:837
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff81bc74d9-ffffffff81bc762b: section_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c40205)
Location: mm/sparse.c:844
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
ffffffff81c40205-ffffffff81c40357: section_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c323b0)
Location: mm/sparse.c:852
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81d50dac)
Location: mm/sparse.c:825
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff81f20fbc)
Location: mm/sparse.c:828
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff820cab9a)
Location: mm/sparse.c:828
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff8214ee2a)
Location: mm/sparse.c:828
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff82231c9a)
Location: mm/sparse.c:828
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffff800010da0798)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
struct page *section_activate(int nid, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000eed38c)
Location: mm/sparse.c:809
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
```
**Symbols:**

```
c000000000eed38c-c000000000eed578: section_activate (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a6da4d)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff81a29f94)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff81ad9e5d)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In mm/sparse.c (ffffffff81ae6313)
Location: mm/sparse.c:809
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
</ul>
<b>Arch</b>
<ul>
</ul>
