# Function: <code>gather_surplus_pages</code>

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
In mm/hugetlb.c (ffffffff811db3b5)
Location: mm/hugetlb.c:1642
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff811f9605)
Location: mm/hugetlb.c:1670
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81209f15)
Location: mm/hugetlb.c:1693
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81215478)
Location: mm/hugetlb.c:1671
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81230048)
Location: mm/hugetlb.c:1677
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81253452)
Location: mm/hugetlb.c:1693
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81267392)
Location: mm/hugetlb.c:1693
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81282df4)
Location: mm/hugetlb.c:1736
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81292914)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5ba0)
Location: mm/hugetlb.c:2061
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812c5ba0-ffffffff812c5e24: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d17f0)
Location: mm/hugetlb.c:2008
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
```
**Symbols:**

```
ffffffff812d17f0-ffffffff812d1a78: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8300)
Location: mm/hugetlb.c:1955
Inline: False
```
**Symbols:**

```
ffffffff812d8300-ffffffff812d8542: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131f100)
Location: mm/hugetlb.c:2219
Inline: False
```
**Symbols:**

```
ffffffff8131f100-ffffffff8131f2ff: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138bb10)
Location: mm/hugetlb.c:2331
Inline: False
```
**Symbols:**

```
ffffffff8138bb10-ffffffff8138bd29: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81409330)
Location: mm/hugetlb.c:2517
Inline: False
```
**Symbols:**

```
ffffffff81409330-ffffffff81409577: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143c990)
Location: mm/hugetlb.c:2545
Inline: False
```
**Symbols:**

```
ffffffff8143c990-ffffffff8143cbd7: gather_surplus_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gather_surplus_pages(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81477160)
Location: mm/hugetlb.c:2644
Inline: False
```
**Symbols:**

```
ffffffff81477160-ffffffff81477360: gather_surplus_pages (STB_LOCAL)
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
In mm/hugetlb.c (ffff800010330270)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (c000000000408db4)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffe00022d714)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff8128aef4)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff8127cd24)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81288d04)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In mm/hugetlb.c (ffffffff81298ab2)
Location: mm/hugetlb.c:1816
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int delta</code> ➡️ <code>long int delta</code>
</li>
</ul>
</details>
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
