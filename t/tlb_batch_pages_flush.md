# Function: <code>tlb_batch_pages_flush</code>

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
In mm/mmu_gather.c (ffffffff8125f1c6)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffff8126d9d6)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffff8129de71)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff812a91f1)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff812ae661)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff812efe01)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81352c90)
Location: mm/mmu_gather.c:45
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff81352c90-ffffffff81352d0d: tlb_batch_pages_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813ccdd0)
Location: mm/mmu_gather.c:84
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff813ccdd0-ffffffff813cce4d: tlb_batch_pages_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401730)
Location: mm/mmu_gather.c:84
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff81401730-ffffffff814017ad: tlb_batch_pages_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142de60)
Location: mm/mmu_gather.c:85
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff8142de60-ffffffff8142dedd: tlb_batch_pages_flush (STB_LOCAL)
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
In mm/mmu_gather.c (ffff800010304c9c)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0522d3c)
Location: mm/mmu_gather.c:44
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
c0522d3c-c0522d94: tlb_batch_pages_flush (STB_LOCAL)
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
In mm/mmu_gather.c (c0000000003d19c0)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210d8e)
Location: mm/mmu_gather.c:44
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffe000210d8e-ffffffe000210dde: tlb_batch_pages_flush (STB_LOCAL)
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
In mm/mmu_gather.c (ffffffff81266026)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffff81258446)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffff81263dc6)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffff81273786)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
