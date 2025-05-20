# Function: <code>arch_tlb_finish_mmu</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2670)
Location: mm/memory.c:275
Inline: False
Direct callers:
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff811f2670-ffffffff811f26e1: arch_tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209630)
Location: mm/memory.c:276
Inline: False
Direct callers:
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff81209630-ffffffff812096a1: arch_tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a4d0)
Location: mm/memory.c:275
Inline: False
Direct callers:
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff8122a4d0-ffffffff8122a541: arch_tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124cdf0)
Location: mm/mmu_gather.c:90
Inline: False
Direct callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff8124cdf0-ffffffff8124ce97: arch_tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
