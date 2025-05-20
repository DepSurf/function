# Function: <code>mc_cpu_online</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f1a0)
Location: arch/x86/kernel/cpu/microcode/core.c:640
Inline: False
```
**Symbols:**

```
ffffffff8104f1a0-ffffffff8104f298: mc_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ef50)
Location: arch/x86/kernel/cpu/microcode/core.c:680
Inline: False
```
**Symbols:**

```
ffffffff8104ef50-ffffffff8104f048: mc_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810528b0)
Location: arch/x86/kernel/cpu/microcode/core.c:786
Inline: False
```
**Symbols:**

```
ffffffff810528b0-ffffffff81052959: mc_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:792
Inline: False
```
**Symbols:**

```
ffffffff810555b0-ffffffff8105564d: mc_cpu_online (STB_LOCAL)
ffffffff81055c77-ffffffff81055c8a: mc_cpu_online.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:793
Inline: False
```
**Symbols:**

```
ffffffff81052c50-ffffffff81052ced: mc_cpu_online (STB_LOCAL)
ffffffff81053317-ffffffff8105332a: mc_cpu_online.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff810559e0-ffffffff81055a10: mc_cpu_online (STB_LOCAL)
ffffffff810564bd-ffffffff810564d1: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff810562b0-ffffffff810562e0: mc_cpu_online (STB_LOCAL)
ffffffff81056d6d-ffffffff81056d81: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:804
Inline: False
```
**Symbols:**

```
ffffffff8105b3d0-ffffffff8105b402: mc_cpu_online (STB_LOCAL)
ffffffff8105bf1d-ffffffff8105bf31: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:802
Inline: False
```
**Symbols:**

```
ffffffff81059e20-ffffffff81059e52: mc_cpu_online (STB_LOCAL)
ffffffff81bd5e90-ffffffff81bd5ea4: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:802
Inline: False
```
**Symbols:**

```
ffffffff8105a800-ffffffff8105a832: mc_cpu_online (STB_LOCAL)
ffffffff81bc823c-ffffffff81bc8250: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:802
Inline: False
```
**Symbols:**

```
ffffffff81063d50-ffffffff81063d82: mc_cpu_online (STB_LOCAL)
ffffffff81c9c0b7-ffffffff81c9c0cb: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:701
Inline: False
```
**Symbols:**

```
ffffffff81070a20-ffffffff81070a58: mc_cpu_online (STB_LOCAL)
ffffffff81e4b4eb-ffffffff81e4b4fe: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81080ef7)
Location: arch/x86/kernel/cpu/microcode/core.c:586
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
```
**Symbols:**

```
ffffffff81080c60-ffffffff81080cb2: mc_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81083360)
Location: arch/x86/kernel/cpu/microcode/core.c:583
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:setup_online_cpu
```
**Symbols:**

```
ffffffff810830b0-ffffffff81083102: mc_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108ac60)
Location: arch/x86/kernel/cpu/microcode/core.c:774
Inline: False
```
**Symbols:**

```
ffffffff8108ac60-ffffffff8108ad71: mc_cpu_online (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff81055e30-ffffffff81055e60: mc_cpu_online (STB_LOCAL)
ffffffff810568ed-ffffffff81056901: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff81046040-ffffffff81046070: mc_cpu_online (STB_LOCAL)
ffffffff81046afd-ffffffff81046b11: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff81056260-ffffffff81056290: mc_cpu_online (STB_LOCAL)
ffffffff81056d1d-ffffffff81056d31: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mc_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:799
Inline: False
```
**Symbols:**

```
ffffffff81057700-ffffffff81057730: mc_cpu_online (STB_LOCAL)
ffffffff810581bd-ffffffff810581d1: mc_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
