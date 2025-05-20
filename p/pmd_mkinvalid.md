# Function: <code>pmd_mkinvalid</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092465)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/pgtable-generic.c (ffffffff812a3784)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81091b05)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/pgtable-generic.c (ffffffff812af064)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092645)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/pgtable-generic.c (ffffffff812b4110)
Location: arch/x86/include/asm/pgtable.h:627
Inline: False
Direct callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
**Symbols:**

```
ffffffff812b4110-ffffffff812b41b3: pmd_mkinvalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810a2365)
Location: arch/x86/include/asm/pgtable.h:598
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/pgtable-generic.c (ffffffff812f5cf0)
Location: arch/x86/include/asm/pgtable.h:598
Inline: False
Direct callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
**Symbols:**

```
ffffffff812f5cf0-ffffffff812f5d93: pmd_mkinvalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad559)
Location: arch/x86/include/asm/pgtable.h:601
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/kmmio.c (ffffffff810b69df)
Location: arch/x86/include/asm/pgtable.h:601
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/pgtable-generic.c (ffffffff81359c20)
Location: arch/x86/include/asm/pgtable.h:601
Inline: False
Direct callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
**Symbols:**

```
ffffffff81359c20-ffffffff81359ccb: pmd_mkinvalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7699)
Location: arch/x86/include/asm/pgtable.h:618
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1c30)
Location: arch/x86/include/asm/pgtable.h:618
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/pgtable-generic.c (ffffffff813d45f0)
Location: arch/x86/include/asm/pgtable.h:618
Inline: False
Direct callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
**Symbols:**

```
ffffffff813d45f0-ffffffff813d46a1: pmd_mkinvalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cadf9)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/kmmio.c (ffffffff810d50e0)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/pgtable-generic.c (ffffffff814095d6)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3349)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd7eb)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In mm/pgtable-generic.c (ffffffff81435dc6)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
</ul>
