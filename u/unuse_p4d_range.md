# Function: <code>unuse_p4d_range</code>

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
In mm/swapfile.c (ffffffff8120d9e2)
Location: mm/swapfile.c:1694
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff81228b92)
Location: mm/swapfile.c:1906
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (ffffffff81249f07)
Location: mm/swapfile.c:1906
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8125e547)
Location: mm/swapfile.c:1878
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8127b7c6)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff8128b2a6)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unuse_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bdc10)
Location: mm/swapfile.c:2052
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812bdc10-ffffffff812bdf48: unuse_p4d_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unuse_p4d_range(struct vm_area_struct *vma, pgd_t *pgd, long unsigned int addr, long unsigned int end, unsigned int type, bool frontswap, long unsigned int *fs_pages_to_unuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9730)
Location: mm/swapfile.c:2068
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812c9730-ffffffff812c9a6c: unuse_p4d_range (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812d03c6)
Location: mm/swapfile.c:2069
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff81315911)
Location: mm/swapfile.c:2056
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff81380eae)
Location: mm/swapfile.c:1949
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff813ff6f9)
Location: mm/swapfile.c:1949
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8143276e)
Location: mm/swapfile.c:1940
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffffffff8146bb8e)
Location: mm/swapfile.c:1948
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/swapfile.c (ffff8000103266d4)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (c053d574)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/swapfile.c (c0000000003fce78)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffe0002267f0)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81283886)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81275740)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81281696)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff812913d1)
Location: mm/swapfile.c:2022
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
