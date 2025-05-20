# Function: <code>collect_cpu_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104cb5d)
Location: arch/x86/kernel/cpu/microcode/core.c:246
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
**Symbols:**

```
ffffffff8104d0a0-ffffffff8104d198: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104cbf8)
Location: arch/x86/kernel/cpu/microcode/core.c:238
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d0d0)
Location: arch/x86/kernel/cpu/microcode/intel.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
```
**Symbols:**

```
ffffffff8104d0d0-ffffffff8104d1df: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ecf0)
Location: arch/x86/kernel/cpu/microcode/core.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f810)
Location: arch/x86/kernel/cpu/microcode/intel.c:735
Inline: False
```
**Symbols:**

```
ffffffff8104ecf0-ffffffff8104ed90: collect_cpu_info (STB_LOCAL)
ffffffff8104f810-ffffffff8104f91f: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ec20)
Location: arch/x86/kernel/cpu/microcode/core.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f750)
Location: arch/x86/kernel/cpu/microcode/intel.c:755
Inline: False
```
**Symbols:**

```
ffffffff8104ec20-ffffffff8104ecc0: collect_cpu_info (STB_LOCAL)
ffffffff8104f750-ffffffff8104f85f: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052590)
Location: arch/x86/kernel/cpu/microcode/core.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053380)
Location: arch/x86/kernel/cpu/microcode/intel.c:764
Inline: False
```
**Symbols:**

```
ffffffff81052590-ffffffff81052630: collect_cpu_info (STB_LOCAL)
ffffffff81053380-ffffffff8105348f: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810552b0)
Location: arch/x86/kernel/cpu/microcode/core.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:765
Inline: False
```
**Symbols:**

```
ffffffff810552b0-ffffffff81055350: collect_cpu_info (STB_LOCAL)
ffffffff81056030-ffffffff81056123: collect_cpu_info (STB_LOCAL)
ffffffff81056f4a-ffffffff81056f71: collect_cpu_info.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052950)
Location: arch/x86/kernel/cpu/microcode/core.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:765
Inline: False
```
**Symbols:**

```
ffffffff81052950-ffffffff810529f0: collect_cpu_info (STB_LOCAL)
ffffffff81053730-ffffffff81053823: collect_cpu_info (STB_LOCAL)
ffffffff810545da-ffffffff81054601: collect_cpu_info.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055b00)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff81055b00-ffffffff81055b9d: collect_cpu_info (STB_LOCAL)
ffffffff810568d0-ffffffff810569bf: collect_cpu_info (STB_LOCAL)
ffffffff810577fb-ffffffff8105781f: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810563d0)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff810563d0-ffffffff8105646d: collect_cpu_info (STB_LOCAL)
ffffffff81057180-ffffffff8105726f: collect_cpu_info (STB_LOCAL)
ffffffff810580db-ffffffff810580ff: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b490)
Location: arch/x86/kernel/cpu/microcode/core.c:361
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff8105b490-ffffffff8105b52c: collect_cpu_info (STB_LOCAL)
ffffffff8105c430-ffffffff8105c51f: collect_cpu_info (STB_LOCAL)
ffffffff8105d2b8-ffffffff8105d2dc: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81059ee0)
Location: arch/x86/kernel/cpu/microcode/core.c:359
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:719
Inline: False
```
**Symbols:**

```
ffffffff81059ee0-ffffffff81059f7c: collect_cpu_info (STB_LOCAL)
ffffffff8105aca0-ffffffff8105ad8f: collect_cpu_info (STB_LOCAL)
ffffffff81bd6028-ffffffff81bd604c: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a8c0)
Location: arch/x86/kernel/cpu/microcode/core.c:359
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:719
Inline: False
```
**Symbols:**

```
ffffffff8105a8c0-ffffffff8105a95c: collect_cpu_info (STB_LOCAL)
ffffffff8105b650-ffffffff8105b740: collect_cpu_info (STB_LOCAL)
ffffffff81bc83d4-ffffffff81bc83f8: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81063e10)
Location: arch/x86/kernel/cpu/microcode/core.c:359
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:719
Inline: False
```
**Symbols:**

```
ffffffff81063e10-ffffffff81063eac: collect_cpu_info (STB_LOCAL)
ffffffff81064c30-ffffffff81064d46: collect_cpu_info (STB_LOCAL)
ffffffff81c9c2b9-ffffffff81c9c2dd: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81070ae0)
Location: arch/x86/kernel/cpu/microcode/core.c:342
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:681
Inline: False
```
**Symbols:**

```
ffffffff81070ae0-ffffffff81070b89: collect_cpu_info (STB_LOCAL)
ffffffff81071610-ffffffff8107174e: collect_cpu_info (STB_LOCAL)
ffffffff81e4b5ee-ffffffff81e4b612: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collect_cpu_info(int cpu_num, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081ed0)
Location: arch/x86/kernel/cpu/microcode/intel.c:549
Inline: False
```
**Symbols:**

```
ffffffff81081ed0-ffffffff81081fe3: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collect_cpu_info(int cpu_num, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81084410)
Location: arch/x86/kernel/cpu/microcode/intel.c:541
Inline: False
```
**Symbols:**

```
ffffffff81084410-ffffffff81084523: collect_cpu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collect_cpu_info(int cpu_num, struct cpu_signature *csig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b9f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:440
Inline: False
```
**Symbols:**

```
ffffffff8108b9f0-ffffffff8108ba0d: collect_cpu_info (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055f50)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff81055f50-ffffffff81055fed: collect_cpu_info (STB_LOCAL)
ffffffff81056d00-ffffffff81056def: collect_cpu_info (STB_LOCAL)
ffffffff81057c5b-ffffffff81057c7f: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046160)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff81046160-ffffffff810461fd: collect_cpu_info (STB_LOCAL)
ffffffff81046f10-ffffffff81046fdf: collect_cpu_info (STB_LOCAL)
ffffffff81047e4b-ffffffff81047e72: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056380)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff81056380-ffffffff8105641d: collect_cpu_info (STB_LOCAL)
ffffffff81057130-ffffffff8105721f: collect_cpu_info (STB_LOCAL)
ffffffff8105808b-ffffffff810580af: collect_cpu_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int collect_cpu_info(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057820)
Location: arch/x86/kernel/cpu/microcode/core.c:366
Inline: False
```
```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:762
Inline: False
```
**Symbols:**

```
ffffffff81057820-ffffffff810578bd: collect_cpu_info (STB_LOCAL)
ffffffff810585d0-ffffffff810586bf: collect_cpu_info (STB_LOCAL)
ffffffff8105952b-ffffffff8105954f: collect_cpu_info.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_num</code>
</li>
<li>
<b>Param added. </b>
<code>struct cpu_signature *csig</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
