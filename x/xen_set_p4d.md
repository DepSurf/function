# Function: <code>xen_set_p4d</code>

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
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024170)
Location: arch/x86/xen/mmu_pv.c:532
Inline: False
```
**Symbols:**

```
ffffffff81024170-ffffffff8102437e: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024d00)
Location: arch/x86/xen/mmu_pv.c:512
Inline: False
```
**Symbols:**

```
ffffffff81024d00-ffffffff81024f17: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810234a0)
Location: arch/x86/xen/mmu_pv.c:520
Inline: False
```
**Symbols:**

```
ffffffff810234a0-ffffffff8102365d: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024b20)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81024b20-ffffffff81024cdd: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81026d50-ffffffff81026f05: xen_set_p4d (STB_LOCAL)
ffffffff81027ca6-ffffffff81027cb9: xen_set_p4d.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026ff0)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81026ff0-ffffffff810271ac: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810283e0)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff810283e0-ffffffff8102851a: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028f00)
Location: arch/x86/xen/mmu_pv.c:487
Inline: False
```
**Symbols:**

```
ffffffff81028f00-ffffffff81029069: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029b00)
Location: arch/x86/xen/mmu_pv.c:487
Inline: False
```
**Symbols:**

```
ffffffff81029b00-ffffffff81029bc2: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102dfc0)
Location: arch/x86/xen/mmu_pv.c:487
Inline: False
```
**Symbols:**

```
ffffffff8102dfc0-ffffffff8102e07f: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81032fb0)
Location: arch/x86/xen/mmu_pv.c:491
Inline: False
```
**Symbols:**

```
ffffffff81032fb0-ffffffff8103309c: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a950)
Location: arch/x86/xen/mmu_pv.c:491
Inline: False
```
**Symbols:**

```
ffffffff8103a950-ffffffff8103aa3c: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103aa20)
Location: arch/x86/xen/mmu_pv.c:507
Inline: False
```
**Symbols:**

```
ffffffff8103aa20-ffffffff8103ab0c: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81040ee0)
Location: arch/x86/xen/mmu_pv.c:507
Inline: False
```
**Symbols:**

```
ffffffff81040ee0-ffffffff81040fcc: xen_set_p4d (STB_LOCAL)
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
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027150)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81027150-ffffffff8102730c: xen_set_p4d (STB_LOCAL)
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
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026fb0)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81026fb0-ffffffff8102716c: xen_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_set_p4d(p4d_t *ptr, p4d_t val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027700)
Location: arch/x86/xen/mmu_pv.c:529
Inline: False
```
**Symbols:**

```
ffffffff81027700-ffffffff81027900: xen_set_p4d (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
