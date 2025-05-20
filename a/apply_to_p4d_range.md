# Function: <code>apply_to_p4d_range</code>

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
In mm/memory.c (ffffffff811f68cf)
Location: mm/memory.c:2124
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff8120ed0d)
Location: mm/memory.c:2241
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff81230b32)
Location: mm/memory.c:2283
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff81242ec2)
Location: mm/memory.c:2019
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff81254d42)
Location: mm/memory.c:2073
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff812632b2)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_to_p4d_range(struct mm_struct *mm, pgd_t *pgd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293240)
Location: mm/memory.c:2303
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff81293240-ffffffff812936b7: apply_to_p4d_range (STB_LOCAL)
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
In mm/memory.c (ffffffff8129dbda)
Location: mm/memory.c:2482
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff812a3689)
Location: mm/memory.c:2527
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff812e4956)
Location: mm/memory.c:2622
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff81346256)
Location: mm/memory.c:2715
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff813be60e)
Location: mm/memory.c:2686
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff813f3267)
Location: mm/memory.c:2686
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffffffff8141df57)
Location: mm/memory.c:2709
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
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
In mm/memory.c (ffff8000102fad18)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (c0518248)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (c0000000003c56e8)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffe00020a65a)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff8125b902)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff8124debc)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff812596a2)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffff812690a2)
Location: mm/memory.c:2078
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
