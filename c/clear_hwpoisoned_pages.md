# Function: <code>clear_hwpoisoned_pages</code>

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
In mm/sparse.c (ffffffff811e388a)
Location: mm/sparse.c:744
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/sparse.c (ffffffff812022d1)
Location: mm/sparse.c:743
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81214111)
Location: mm/sparse.c:743
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f502)
Location: mm/sparse.c:814
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/sparse.c (ffffffff8123a73c)
Location: mm/sparse.c:826
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/sparse.c (ffffffff8125dcb9)
Location: mm/sparse.c:803
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/sparse.c (ffffffff8127251b)
Location: mm/sparse.c:732
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
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
In mm/sparse.c (ffffffff8128dce5)
Location: mm/sparse.c:883
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff8129d9e5)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d1685)
Location: mm/sparse.c:932
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd1a5)
Location: mm/sparse.c:939
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff812e4a03)
Location: mm/sparse.c:947
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff8132bc83)
Location: mm/sparse.c:920
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_hwpoisoned_pages(struct page *memmap, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813dd740)
Location: mm/memory-failure.c:2383
Inline: False
Direct callers:
  - mm/sparse.c:sparse_remove_section
```
**Symbols:**

```
ffffffff813dd740-ffffffff813dd793: clear_hwpoisoned_pages (STB_GLOBAL)
```
</details>
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
In mm/sparse.c (ffff80001033cb28)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (c000000000417cc0)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff81295fc5)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff81287bd5)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff81293dd5)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
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
In mm/sparse.c (ffffffff812a3c35)
Location: mm/sparse.c:912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
