# Function: <code>return_unused_surplus_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff811db310)
Location: mm/hugetlb.c:1730
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff811db310-ffffffff811db361: return_unused_surplus_pages.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff811f980d)
Location: mm/hugetlb.c:1758
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff811f9560-ffffffff811f95be: return_unused_surplus_pages.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812097b0)
Location: mm/hugetlb.c:1789
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812097b0-ffffffff81209827: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81215040)
Location: mm/hugetlb.c:1769
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81215040-ffffffff812150b7: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122fd30)
Location: mm/hugetlb.c:1775
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff8122fd30-ffffffff8122fda7: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252190)
Location: mm/hugetlb.c:1791
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81252190-ffffffff81252207: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81267290)
Location: mm/hugetlb.c:1791
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81267290-ffffffff81267307: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281710)
Location: mm/hugetlb.c:1834
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81281710-ffffffff81281780: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291210)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81291210-ffffffff81291280: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4d30)
Location: mm/hugetlb.c:2160
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812c4d30-ffffffff812c4da0: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0aa0)
Location: mm/hugetlb.c:2110
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812d0aa0-ffffffff812d0b10: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7330)
Location: mm/hugetlb.c:2052
Inline: False
```
**Symbols:**

```
ffffffff812d7330-ffffffff812d742c: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131db30)
Location: mm/hugetlb.c:2312
Inline: False
```
**Symbols:**

```
ffffffff8131db30-ffffffff8131dc02: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81388f70)
Location: mm/hugetlb.c:2424
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
```
**Symbols:**

```
ffffffff81388f70-ffffffff81389073: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814086b0)
Location: mm/hugetlb.c:2609
Inline: False
```
**Symbols:**

```
ffffffff814086b0-ffffffff814087e4: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143b5b0)
Location: mm/hugetlb.c:2638
Inline: False
```
**Symbols:**

```
ffffffff8143b5b0-ffffffff8143b6e4: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81474170)
Location: mm/hugetlb.c:2736
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
```
**Symbols:**

```
ffffffff81474170-ffffffff81474241: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032f8a8)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffff80001032f8a8-ffff80001032f964: return_unused_surplus_pages (STB_LOCAL)
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
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407340)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
c000000000407340-c000000000407430: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022d5d0)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffe00022d5d0-ffffffe00022d662: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812897f0)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812897f0-ffffffff81289860: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127b690)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff8127b690-ffffffff8127b700: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287600)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81287600-ffffffff81287670: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate *h, long unsigned int unused_resv_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297d40)
Location: mm/hugetlb.c:1914
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff81297d40-ffffffff81297db0: return_unused_surplus_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
