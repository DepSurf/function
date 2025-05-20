# Function: <code>remap_p4d_range</code>

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
In mm/memory.c (ffffffff811f6d21)
Location: mm/memory.c:1912
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8120f249)
Location: mm/memory.c:2029
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8122f047)
Location: mm/memory.c:2069
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff812433ca)
Location: mm/memory.c:1805
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff812551fa)
Location: mm/memory.c:1858
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8126376a)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff812939e4)
Location: mm/memory.c:2062
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8129e2f3)
Location: mm/memory.c:2236
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff812a39bd)
Location: mm/memory.c:2254
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
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
In mm/memory.c (ffffffff812e4cd7)
Location: mm/memory.c:2349
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
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
In mm/memory.c (ffffffff813465e7)
Location: mm/memory.c:2442
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
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
In mm/memory.c (ffffffff813be9c6)
Location: mm/memory.c:2413
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int remap_p4d_range(struct mm_struct *mm, pgd_t *pgd, long unsigned int addr, long unsigned int end, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f3520)
Location: mm/memory.c:2413
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
```
**Symbols:**

```
ffffffff813f3520-ffffffff813f3911: remap_p4d_range (STB_LOCAL)
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
In mm/memory.c (ffffffff8141e360)
Location: mm/memory.c:2436
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
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
In mm/memory.c (ffff8000102fa8f0)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (c0517a48)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (c0000000003c500c)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffe00020a39a)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8125bdba)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8124e369)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff81259b5a)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff8126955a)
Location: mm/memory.c:1863
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
