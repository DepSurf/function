# Function: <code>get_old_pmd</code>

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
In mm/mremap.c (ffffffff811c9359)
Location: mm/mremap.c:32
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff811e573f)
Location: mm/mremap.c:31
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff811f597e)
Location: mm/mremap.c:31
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81200744)
Location: mm/mremap.c:32
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81218f0a)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8123a8ca)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8124ead3)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81260e28)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8126f5c1)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t *get_old_pmd(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8129fa40)
Location: mm/mremap.c:33
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff8129fa40-ffffffff8129fbfa: get_old_pmd (STB_LOCAL)
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
In mm/mremap.c (ffffffff812aba20)
Location: mm/mremap.c:54
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff812b0e1b)
Location: mm/mremap.c:53
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff812f256d)
Location: mm/mremap.c:54
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81356413)
Location: mm/mremap.c:54
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff813d0a39)
Location: mm/mremap.c:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff8140545b)
Location: mm/mremap.c:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81431972)
Location: mm/mremap.c:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffff800010305eb0)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0523e34)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d3bb4)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffe000211ac4)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81267c11)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81259f69)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff812659b1)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In mm/mremap.c (ffffffff81275353)
Location: mm/mremap.c:33
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
