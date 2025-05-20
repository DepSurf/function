# Function: <code>tlb_flush_mmu_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bb890)
Location: mm/memory.c:250
Inline: False
Direct callers:
  - mm/memory.c:tlb_finish_mmu
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff811bb890-ffffffff811bb8e1: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d62c0)
Location: mm/memory.c:254
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff811d62c0-ffffffff811d6311: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6250)
Location: mm/memory.c:254
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff811e6250-ffffffff811e62a1: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1320)
Location: mm/memory.c:254
Inline: False
Direct callers:
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff811f1320-ffffffff811f1371: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81207fa0)
Location: mm/memory.c:255
Inline: False
Direct callers:
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff81207fa0-ffffffff81207ff1: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229260)
Location: mm/memory.c:251
Inline: False
Direct callers:
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff81229260-ffffffff812292bf: tlb_flush_mmu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_flush_mmu_free(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124cc90)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
```
**Symbols:**

```
ffffffff8124cc90-ffffffff8124cce8: tlb_flush_mmu_free (STB_GLOBAL)
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
In mm/mmu_gather.c (ffffffff8125f1ba)
Location: mm/mmu_gather.c:178
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
In mm/mmu_gather.c (ffffffff8126d9ca)
Location: mm/mmu_gather.c:178
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
In mm/mmu_gather.c (ffffffff8129de52)
Location: mm/mmu_gather.c:238
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
In mm/mmu_gather.c (ffffffff812a91d2)
Location: mm/mmu_gather.c:238
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
In mm/mmu_gather.c (ffffffff812ae642)
Location: mm/mmu_gather.c:238
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
In mm/mmu_gather.c (ffffffff812efde2)
Location: mm/mmu_gather.c:238
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff813532ec)
Location: mm/mmu_gather.c:251
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff813cd5ac)
Location: mm/mmu_gather.c:288
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff81401f0c)
Location: mm/mmu_gather.c:288
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff8142e55c)
Location: mm/mmu_gather.c:289
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffff800010304c8c)
Location: mm/mmu_gather.c:178
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (c05230f0)
Location: mm/mmu_gather.c:178
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (c0000000003d192c)
Location: mm/mmu_gather.c:178
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/mmu_gather.c (ffffffe000211006)
Location: mm/mmu_gather.c:178
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/mmu_gather.c (ffffffff8126601a)
Location: mm/mmu_gather.c:178
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
In mm/mmu_gather.c (ffffffff8125843a)
Location: mm/mmu_gather.c:178
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
In mm/mmu_gather.c (ffffffff81263dba)
Location: mm/mmu_gather.c:178
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
In mm/mmu_gather.c (ffffffff8127377a)
Location: mm/mmu_gather.c:178
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
</ul>
