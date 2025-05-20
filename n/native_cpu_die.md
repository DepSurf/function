# Function: <code>native_cpu_die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052730)
Location: arch/x86/kernel/smpboot.c:1527
Inline: False
```
**Symbols:**

```
ffffffff81052730-ffffffff81052740: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052840)
Location: arch/x86/kernel/smpboot.c:1554
Inline: False
```
**Symbols:**

```
ffffffff81052840-ffffffff81052850: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81055150)
Location: arch/x86/kernel/smpboot.c:1582
Inline: False
```
**Symbols:**

```
ffffffff81055150-ffffffff81055160: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054a70)
Location: arch/x86/kernel/smpboot.c:1588
Inline: False
```
**Symbols:**

```
ffffffff81054a70-ffffffff81054a80: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81058830)
Location: arch/x86/kernel/smpboot.c:1501
Inline: False
```
**Symbols:**

```
ffffffff81058830-ffffffff81058840: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105b4a0)
Location: arch/x86/kernel/smpboot.c:1557
Inline: False
```
**Symbols:**

```
ffffffff8105b4a0-ffffffff8105b4b0: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81061120)
Location: arch/x86/kernel/smpboot.c:1558
Inline: False
```
**Symbols:**

```
ffffffff81061120-ffffffff81061130: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810647d0)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff810647d0-ffffffff810647e0: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064e50)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81064e50-ffffffff81064e60: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1650
Inline: False
```
**Symbols:**

```
ffffffff8106bb93-ffffffff8106bbbb: native_cpu_die.cold (STB_LOCAL)
ffffffff8106b550-ffffffff8106b583: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1644
Inline: False
```
**Symbols:**

```
ffffffff81bd6b00-ffffffff81bd6b28: native_cpu_die.cold (STB_LOCAL)
ffffffff8106d1c0-ffffffff8106d1f3: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1645
Inline: False
```
**Symbols:**

```
ffffffff81bc8cda-ffffffff81bc8d02: native_cpu_die.cold (STB_LOCAL)
ffffffff8106dc60-ffffffff8106dc93: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1652
Inline: False
```
**Symbols:**

```
ffffffff81c9d680-ffffffff81c9d6a8: native_cpu_die.cold (STB_LOCAL)
ffffffff81079470-ffffffff810794a3: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81e4cb17-ffffffff81e4cb3d: native_cpu_die.cold (STB_LOCAL)
ffffffff810882f0-ffffffff8108832b: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bd50)
Location: arch/x86/kernel/smpboot.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8109bd50-ffffffff8109bdb1: native_cpu_die (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064940)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81064940-ffffffff81064950: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054c30)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81054c30-ffffffff81054c40: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064df0)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81064df0-ffffffff81064e00: native_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810663d0)
Location: arch/x86/kernel/smpboot.c:1623
Inline: False
```
**Symbols:**

```
ffffffff810663d0-ffffffff810663e0: native_cpu_die (STB_GLOBAL)
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
