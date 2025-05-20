# Function: <code>remap_pte_range</code>

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
In mm/memory.c (ffffffff811c09a8)
Location: mm/memory.c:1622
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff811dc2e4)
Location: mm/memory.c:1684
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff811ebdfb)
Location: mm/memory.c:1684
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
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
In mm/memory.c (ffffffff811f6d21)
Location: mm/memory.c:1850
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
Location: mm/memory.c:1967
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
In mm/memory.c (ffffffff8122f170)
Location: mm/memory.c:1998
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
In mm/memory.c (ffffffff812434f6)
Location: mm/memory.c:1734
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
In mm/memory.c (ffffffff8125532b)
Location: mm/memory.c:1787
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
In mm/memory.c (ffffffff8126389b)
Location: mm/memory.c:1792
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remap_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128de60)
Location: mm/memory.c:1991
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff8128de60-ffffffff8128e03c: remap_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remap_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81298b00)
Location: mm/memory.c:2165
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81298b00-ffffffff81298cd4: remap_pte_range (STB_LOCAL)
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
In mm/memory.c (ffffffff812a3b3b)
Location: mm/memory.c:2183
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
In mm/memory.c (ffffffff812e4e57)
Location: mm/memory.c:2278
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
In mm/memory.c (ffffffff81346787)
Location: mm/memory.c:2371
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
In mm/memory.c (ffffffff813beb76)
Location: mm/memory.c:2342
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
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
In mm/memory.c (ffffffff813f36e2)
Location: mm/memory.c:2342
Inline: True
Inline callers:
  - mm/memory.c:remap_p4d_range
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
In mm/memory.c (ffffffff8141e501)
Location: mm/memory.c:2365
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
In mm/memory.c (ffff8000102fa994)
Location: mm/memory.c:1792
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
In mm/memory.c (c0517a50)
Location: mm/memory.c:1792
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
In mm/memory.c (c0000000003c5158)
Location: mm/memory.c:1792
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
Location: mm/memory.c:1792
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
In mm/memory.c (ffffffff8125beeb)
Location: mm/memory.c:1792
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
In mm/memory.c (ffffffff8124e490)
Location: mm/memory.c:1792
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
In mm/memory.c (ffffffff81259c8b)
Location: mm/memory.c:1792
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
In mm/memory.c (ffffffff8126968b)
Location: mm/memory.c:1792
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
