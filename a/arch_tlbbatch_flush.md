# Function: <code>arch_tlbbatch_flush</code>

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
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074d10)
Location: arch/x86/mm/tlb.c:319
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff81074d10-ffffffff81074dd5: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107aea0)
Location: arch/x86/mm/tlb.c:681
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8107aea0-ffffffff8107af6d: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107dc60)
Location: arch/x86/mm/tlb.c:694
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8107dc60-ffffffff8107dd2d: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810847d0)
Location: arch/x86/mm/tlb.c:806
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810847d0-ffffffff810848a5: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088470)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff81088470-ffffffff81088500: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089120)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff81089120-ffffffff810891b0: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ba40)
Location: arch/x86/mm/tlb.c:1198
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8108ba40-ffffffff8108bad2: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ba90)
Location: arch/x86/mm/tlb.c:1134
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8108ba90-ffffffff8108bb22: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c680)
Location: arch/x86/mm/tlb.c:1166
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8108c680-ffffffff8108c73e: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bec0)
Location: arch/x86/mm/tlb.c:1225
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8109bec0-ffffffff8109bf7e: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af440)
Location: arch/x86/mm/tlb.c:1195
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810af440-ffffffff810af54b: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c98a0)
Location: arch/x86/mm/tlb.c:1219
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810c98a0-ffffffff810c99ae: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccf20)
Location: arch/x86/mm/tlb.c:1240
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810ccf20-ffffffff810cd029: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d55f0)
Location: arch/x86/mm/tlb.c:1249
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810d55f0-ffffffff810d56f9: arch_tlbbatch_flush (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810880e0)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff810880e0-ffffffff81088170: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076d40)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff81076d40-ffffffff81076dc4: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088090)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff81088090-ffffffff81088120: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_tlbbatch_flush(struct arch_tlbflush_unmap_batch *batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a310)
Location: arch/x86/mm/tlb.c:858
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_flush_dirty
```
**Symbols:**

```
ffffffff8108a310-ffffffff8108a3bb: arch_tlbbatch_flush (STB_GLOBAL)
```
</details>
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
