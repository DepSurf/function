# Function: <code>flush_tlb_multi</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c6ed)
Location: arch/x86/mm/tlb.c:865
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8108c2a0-ffffffff8108c2b2: flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bf2d)
Location: arch/x86/mm/tlb.c:924
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8109bac0-ffffffff8109bad2: flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af517)
Location: arch/x86/mm/tlb.c:898
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810aef20-ffffffff810aef4b: flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c9999)
Location: arch/x86/mm/tlb.c:921
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810c92b0-ffffffff810c92db: flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cd014)
Location: arch/x86/mm/tlb.c:940
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810cc940-ffffffff810cc96b: flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d56e4)
Location: arch/x86/mm/tlb.c:941
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810d4fd0-ffffffff810d4ffb: flush_tlb_multi (STB_GLOBAL)
```
</details>
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
