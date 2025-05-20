# Function: <code>xen_set_pmd_hyper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ff50)
Location: arch/x86/xen/mmu.c:253
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8101ff50-ffffffff81020068: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ff50)
Location: arch/x86/xen/mmu.c:254
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8101ff50-ffffffff81020056: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020610)
Location: arch/x86/xen/mmu.c:254
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81020610-ffffffff81020716: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020fa0)
Location: arch/x86/xen/mmu_pv.c:221
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81020fa0-ffffffff810210a7: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021ed0)
Location: arch/x86/xen/mmu_pv.c:201
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81021ed0-ffffffff81021fdd: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022a50)
Location: arch/x86/xen/mmu_pv.c:210
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81022a50-ffffffff81022b66: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021fd0)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81021fd0-ffffffff810220e6: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024c50)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81024c50-ffffffff81024d66: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025230)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81025230-ffffffff81025346: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028221)
Location: arch/x86/xen/mmu_pv.c:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81027820-ffffffff810278c6: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028e22)
Location: arch/x86/xen/mmu_pv.c:208
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81027700-ffffffff810277e8: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029f0e)
Location: arch/x86/xen/mmu_pv.c:208
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81029c20-ffffffff81029c67: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102e4fb)
Location: arch/x86/xen/mmu_pv.c:208
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8102e210-ffffffff8102e257: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810335b0)
Location: arch/x86/xen/mmu_pv.c:210
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff810335b0-ffffffff81033639: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103afb0)
Location: arch/x86/xen/mmu_pv.c:210
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8103afb0-ffffffff8103b039: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103b080)
Location: arch/x86/xen/mmu_pv.c:226
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8103b080-ffffffff8103b109: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81041540)
Location: arch/x86/xen/mmu_pv.c:226
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81041540-ffffffff810415c9: xen_set_pmd_hyper (STB_LOCAL)
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
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025390)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81025390-ffffffff810254a6: xen_set_pmd_hyper (STB_LOCAL)
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
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810251f0)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff810251f0-ffffffff81025306: xen_set_pmd_hyper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_set_pmd_hyper(pmd_t *ptr, pmd_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025bc0)
Location: arch/x86/xen/mmu_pv.c:219
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81025bc0-ffffffff81025d33: xen_set_pmd_hyper (STB_LOCAL)
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
