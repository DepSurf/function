# Function: <code>collect_cpu_info_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e110)
Location: arch/x86/kernel/cpu/microcode/amd.c:552
Inline: False
```
**Symbols:**

```
ffffffff8104e110-ffffffff8104e1e0: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e2a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:564
Inline: False
```
**Symbols:**

```
ffffffff8104e2a0-ffffffff8104e370: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050920)
Location: arch/x86/kernel/cpu/microcode/amd.c:579
Inline: False
```
**Symbols:**

```
ffffffff81050920-ffffffff810509f0: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050820)
Location: arch/x86/kernel/cpu/microcode/amd.c:439
Inline: False
```
**Symbols:**

```
ffffffff81050820-ffffffff810508f2: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054de0)
Location: arch/x86/kernel/cpu/microcode/amd.c:442
Inline: False
```
**Symbols:**

```
ffffffff81054de0-ffffffff81054eb2: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:442
Inline: True
```
**Symbols:**

```
ffffffff81057ad0-ffffffff81057b59: collect_cpu_info_amd (STB_LOCAL)
ffffffff81057d40-ffffffff81057d8b: collect_cpu_info_amd.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810556ac)
Location: arch/x86/kernel/cpu/microcode/amd.c:649
Inline: True
```
**Symbols:**

```
ffffffff81055470-ffffffff810554f9: collect_cpu_info_amd (STB_LOCAL)
ffffffff81055697-ffffffff810556e2: collect_cpu_info_amd.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810588e2)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff810586a0-ffffffff81058728: collect_cpu_info_amd (STB_LOCAL)
ffffffff810588c9-ffffffff81058919: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810591b2)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff81058f70-ffffffff81058ff8: collect_cpu_info_amd (STB_LOCAL)
ffffffff81059199-ffffffff810591e9: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: False
```
**Symbols:**

```
ffffffff8105dc70-ffffffff8105dcf7: collect_cpu_info_amd (STB_LOCAL)
ffffffff8105e3d2-ffffffff8105e41c: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:646
Inline: False
```
**Symbols:**

```
ffffffff8105c310-ffffffff8105c397: collect_cpu_info_amd (STB_LOCAL)
ffffffff81bd61aa-ffffffff81bd61f4: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:646
Inline: False
```
**Symbols:**

```
ffffffff8105cc20-ffffffff8105cca7: collect_cpu_info_amd (STB_LOCAL)
ffffffff81bc8575-ffffffff81bc85c1: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:646
Inline: False
```
**Symbols:**

```
ffffffff810662c0-ffffffff81066361: collect_cpu_info_amd (STB_LOCAL)
ffffffff81c9c46d-ffffffff81c9c4b9: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:652
Inline: False
```
**Symbols:**

```
ffffffff81073030-ffffffff810730de: collect_cpu_info_amd (STB_LOCAL)
ffffffff81e4b78f-ffffffff81e4b7f3: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083080)
Location: arch/x86/kernel/cpu/microcode/amd.c:663
Inline: False
```
**Symbols:**

```
ffffffff81083080-ffffffff81083195: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084ec0)
Location: arch/x86/kernel/cpu/microcode/amd.c:658
Inline: False
```
**Symbols:**

```
ffffffff81084ec0-ffffffff81084fd5: collect_cpu_info_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c150)
Location: arch/x86/kernel/cpu/microcode/amd.c:627
Inline: False
```
**Symbols:**

```
ffffffff8108c150-ffffffff8108c24e: collect_cpu_info_amd (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058d32)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff81058af0-ffffffff81058b78: collect_cpu_info_amd (STB_LOCAL)
ffffffff81058d19-ffffffff81058d69: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048ea9)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff810483f0-ffffffff81048446: collect_cpu_info_amd (STB_LOCAL)
ffffffff81048e90-ffffffff81048ec8: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059162)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff81058f20-ffffffff81058fa8: collect_cpu_info_amd (STB_LOCAL)
ffffffff81059149-ffffffff81059199: collect_cpu_info_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int collect_cpu_info_amd(int cpu, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a602)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: True
```
**Symbols:**

```
ffffffff8105a3c0-ffffffff8105a448: collect_cpu_info_amd (STB_LOCAL)
ffffffff8105a5e9-ffffffff8105a639: collect_cpu_info_amd.cold (STB_LOCAL)
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
