# Function: <code>xen_set_pud_hyper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101fd70)
Location: arch/x86/xen/mmu.c:446
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pud
```
**Symbols:**

```
ffffffff8101fd70-ffffffff8101fe88: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101fd80)
Location: arch/x86/xen/mmu.c:447
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pud
```
**Symbols:**

```
ffffffff8101fd80-ffffffff8101fe86: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020440)
Location: arch/x86/xen/mmu.c:447
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pud
```
**Symbols:**

```
ffffffff81020440-ffffffff81020546: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021170)
Location: arch/x86/xen/mmu_pv.c:412
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81021170-ffffffff81021277: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021d00)
Location: arch/x86/xen/mmu_pv.c:392
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81021d00-ffffffff81021e0d: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810228a0)
Location: arch/x86/xen/mmu_pv.c:401
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff810228a0-ffffffff810229b6: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022180)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81022180-ffffffff81022296: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024aa0)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81024aa0-ffffffff81024bb6: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025080)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81025080-ffffffff81025196: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028341)
Location: arch/x86/xen/mmu_pv.c:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81027770-ffffffff81027816: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028cd2)
Location: arch/x86/xen/mmu_pv.c:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81027610-ffffffff810276f8: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029fae)
Location: arch/x86/xen/mmu_pv.c:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81029bd0-ffffffff81029c17: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102e59b)
Location: arch/x86/xen/mmu_pv.c:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff8102e1c0-ffffffff8102e207: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81033480)
Location: arch/x86/xen/mmu_pv.c:393
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81033480-ffffffff81033509: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103ae60)
Location: arch/x86/xen/mmu_pv.c:393
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff8103ae60-ffffffff8103aee9: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103af30)
Location: arch/x86/xen/mmu_pv.c:409
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff8103af30-ffffffff8103afb9: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810413f0)
Location: arch/x86/xen/mmu_pv.c:409
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff810413f0-ffffffff81041479: xen_set_pud_hyper (STB_LOCAL)
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
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810251e0)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff810251e0-ffffffff810252f6: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025040)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff81025040-ffffffff81025156: xen_set_pud_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_set_pud_hyper(pud_t *ptr, pud_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810259a0)
Location: arch/x86/xen/mmu_pv.c:410
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pud
```
**Symbols:**

```
ffffffff810259a0-ffffffff81025b13: xen_set_pud_hyper (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
