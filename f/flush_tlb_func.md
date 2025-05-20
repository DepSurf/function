# Function: <code>flush_tlb_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810725f0)
Location: arch/x86/mm/tlb.c:101
Inline: True
```
**Symbols:**

```
ffffffff810725f0-ffffffff8107274f: flush_tlb_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810722e0)
Location: arch/x86/mm/tlb.c:215
Inline: True
```
**Symbols:**

```
ffffffff810722e0-ffffffff8107240b: flush_tlb_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81075e50)
Location: arch/x86/mm/tlb.c:230
Inline: True
```
**Symbols:**

```
ffffffff81075e50-ffffffff81075f7b: flush_tlb_func (STB_LOCAL)
```
</details>
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
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bd20)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8108bd20-ffffffff8108bf00: flush_tlb_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:722
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff8109b470-ffffffff8109b6b5: flush_tlb_func (STB_LOCAL)
ffffffff81ca1199-ffffffff81ca11e0: flush_tlb_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:723
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810ae980-ffffffff810aec1b: flush_tlb_func (STB_LOCAL)
ffffffff81e507b3-ffffffff81e50801: flush_tlb_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:723
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810c8cc0-ffffffff810c8f63: flush_tlb_func (STB_LOCAL)
ffffffff82054c38-ffffffff82054c86: flush_tlb_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:742
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810cc300-ffffffff810cc5a2: flush_tlb_func (STB_LOCAL)
ffffffff820d3216-ffffffff820d325e: flush_tlb_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void flush_tlb_func(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:743
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
**Symbols:**

```
ffffffff810d4990-ffffffff810d4c32: flush_tlb_func (STB_LOCAL)
ffffffff821ae084-ffffffff821ae0cc: flush_tlb_func.cold (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
