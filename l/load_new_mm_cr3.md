# Function: <code>load_new_mm_cr3</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107a250)
Location: arch/x86/mm/tlb.c:104
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8107a250-ffffffff8107a33f: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d000)
Location: arch/x86/mm/tlb.c:104
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8107d000-ffffffff8107d0d7: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81083a40)
Location: arch/x86/mm/tlb.c:112
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81083a40-ffffffff81083b17: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810876e0)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810876e0-ffffffff810877c2: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810883d0)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810883d0-ffffffff810884b2: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ab50)
Location: arch/x86/mm/tlb.c:269
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8108ab50-ffffffff8108ac31: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ace0)
Location: arch/x86/mm/tlb.c:268
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8108ace0-ffffffff8108adc1: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b770)
Location: arch/x86/mm/tlb.c:269
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8108b770-ffffffff8108b83c: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109ad50)
Location: arch/x86/mm/tlb.c:276
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8109ad50-ffffffff8109ae1c: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae140)
Location: arch/x86/mm/tlb.c:277
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810ae140-ffffffff810ae232: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8400)
Location: arch/x86/mm/tlb.c:277
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810c8400-ffffffff810c84f2: load_new_mm_cr3 (STB_LOCAL)
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
In arch/x86/mm/tlb.c (ffffffff810cbe7d)
Location: arch/x86/mm/tlb.c:281
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/mm/tlb.c (ffffffff810d450d)
Location: arch/x86/mm/tlb.c:282
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810873d0)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810873d0-ffffffff810874b2: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81075fa0)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81075fa0-ffffffff81076077: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087380)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81087380-ffffffff81087462: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void load_new_mm_cr3(pgd_t *pgdir, u16 new_asid, bool need_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810894b0)
Location: arch/x86/mm/tlb.c:113
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810894b0-ffffffff81089592: load_new_mm_cr3 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
