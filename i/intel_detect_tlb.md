# Function: <code>intel_detect_tlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041980)
Location: arch/x86/kernel/cpu/intel.c:695
Inline: False
```
**Symbols:**

```
ffffffff81041980-ffffffff81041e24: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810418b0)
Location: arch/x86/kernel/cpu/intel.c:737
Inline: False
```
**Symbols:**

```
ffffffff810418b0-ffffffff81041d06: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041300)
Location: arch/x86/kernel/cpu/intel.c:776
Inline: False
```
**Symbols:**

```
ffffffff81041300-ffffffff81041756: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8103f410)
Location: arch/x86/kernel/cpu/intel.c:799
Inline: True
```
**Symbols:**

```
ffffffff8103f410-ffffffff8103f8d9: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81042750)
Location: arch/x86/kernel/cpu/intel.c:854
Inline: True
```
**Symbols:**

```
ffffffff81042750-ffffffff81042c1d: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81044570)
Location: arch/x86/kernel/cpu/intel.c:933
Inline: True
```
**Symbols:**

```
ffffffff81044570-ffffffff81044a31: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81045ff0)
Location: arch/x86/kernel/cpu/intel.c:941
Inline: True
```
**Symbols:**

```
ffffffff81045ff0-ffffffff810464cd: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81048a10)
Location: arch/x86/kernel/cpu/intel.c:936
Inline: True
```
**Symbols:**

```
ffffffff81048a10-ffffffff81048ea5: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810492e0)
Location: arch/x86/kernel/cpu/intel.c:942
Inline: True
```
**Symbols:**

```
ffffffff810492e0-ffffffff81049775: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104da90)
Location: arch/x86/kernel/cpu/intel.c:893
Inline: True
```
**Symbols:**

```
ffffffff8104da90-ffffffff8104db7f: intel_detect_tlb.part.0 (STB_LOCAL)
ffffffff8104db80-ffffffff8104db97: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104cfc0)
Location: arch/x86/kernel/cpu/intel.c:894
Inline: True
```
**Symbols:**

```
ffffffff8104cfc0-ffffffff8104d0af: intel_detect_tlb.part.0 (STB_LOCAL)
ffffffff8104d0b0-ffffffff8104d0c7: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104eb50)
Location: arch/x86/kernel/cpu/intel.c:899
Inline: True
```
**Symbols:**

```
ffffffff8104eb50-ffffffff8104ec49: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81056bc0)
Location: arch/x86/kernel/cpu/intel.c:903
Inline: True
```
**Symbols:**

```
ffffffff81056bc0-ffffffff81056cb9: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81062e00)
Location: arch/x86/kernel/cpu/intel.c:931
Inline: False
```
**Symbols:**

```
ffffffff81062e00-ffffffff81062f2f: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81071c60)
Location: arch/x86/kernel/cpu/intel.c:1073
Inline: False
```
**Symbols:**

```
ffffffff81071c60-ffffffff81071d8f: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81073850)
Location: arch/x86/kernel/cpu/intel.c:1073
Inline: False
```
**Symbols:**

```
ffffffff81073850-ffffffff8107397f: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107ac70)
Location: arch/x86/kernel/cpu/intel.c:890
Inline: False
```
**Symbols:**

```
ffffffff8107ac70-ffffffff8107ad9f: intel_detect_tlb (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049450)
Location: arch/x86/kernel/cpu/intel.c:942
Inline: True
```
**Symbols:**

```
ffffffff81049450-ffffffff810498e5: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81038820)
Location: arch/x86/kernel/cpu/intel.c:942
Inline: False
```
**Symbols:**

```
ffffffff81038820-ffffffff81038c99: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049290)
Location: arch/x86/kernel/cpu/intel.c:942
Inline: True
```
**Symbols:**

```
ffffffff81049290-ffffffff81049725: intel_detect_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void intel_detect_tlb(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a6a0)
Location: arch/x86/kernel/cpu/intel.c:942
Inline: True
```
**Symbols:**

```
ffffffff8104a6a0-ffffffff8104ab35: intel_detect_tlb (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
