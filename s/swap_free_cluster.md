# Function: <code>swap_free_cluster</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e140)
Location: mm/swapfile.c:861
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff812295d9)
Location: mm/swapfile.c:893
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8124a8a0)
Location: mm/swapfile.c:893
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8125eeae)
Location: mm/swapfile.c:929
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff81279b42)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff81289622)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swap_free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb440)
Location: mm/swapfile.c:1004
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812bb440-ffffffff812bb590: swap_free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swap_free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6ee0)
Location: mm/swapfile.c:1019
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812c6ee0-ffffffff812c7030: swap_free_cluster (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812ce6cf)
Location: mm/swapfile.c:1018
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff81313c5f)
Location: mm/swapfile.c:1026
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8137f344)
Location: mm/swapfile.c:1030
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff813fde6e)
Location: mm/swapfile.c:1033
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swap_free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142ede0)
Location: mm/swapfile.c:1035
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff8142ede0-ffffffff8142ef41: swap_free_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swap_free_cluster(struct swap_info_struct *si, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468960)
Location: mm/swapfile.c:1035
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
```
**Symbols:**

```
ffffffff81468960-ffffffff81468ac1: swap_free_cluster (STB_LOCAL)
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:964
Inline: False
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:964
Inline: False
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:964
Inline: False
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
In mm/swapfile.c (0)
Location: mm/swapfile.c:964
Inline: False
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
In mm/swapfile.c (ffffffff81281c02)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff81273722)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8127fa12)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8128f6e0)
Location: mm/swapfile.c:964
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
