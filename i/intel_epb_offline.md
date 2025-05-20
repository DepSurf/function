# Function: <code>intel_epb_offline</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81049990)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff81049990-ffffffff810499c8: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a320)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104a320-ffffffff8104a358: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104eb20)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104eb20-ffffffff8104eb58: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104de30)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104de30-ffffffff8104de68: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104fac0)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104fac0-ffffffff8104faf8: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff81057d40-ffffffff81057d91: intel_epb_offline (STB_LOCAL)
ffffffff81c9b1f2-ffffffff81c9b20e: intel_epb_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: arch/x86/kernel/cpu/intel_epb.c:195
Inline: False
```
**Symbols:**

```
ffffffff81064220-ffffffff81064281: intel_epb_offline (STB_LOCAL)
ffffffff81e4a72d-ffffffff81e4a749: intel_epb_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: arch/x86/kernel/cpu/intel_epb.c:195
Inline: False
```
**Symbols:**

```
ffffffff81073410-ffffffff81073471: intel_epb_offline (STB_LOCAL)
ffffffff82052ba3-ffffffff82052bbf: intel_epb_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: arch/x86/kernel/cpu/intel_epb.c:195
Inline: False
```
**Symbols:**

```
ffffffff81074ff0-ffffffff81075051: intel_epb_offline (STB_LOCAL)
ffffffff820d1070-ffffffff820d108c: intel_epb_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (0)
Location: arch/x86/kernel/cpu/intel_epb.c:195
Inline: False
```
**Symbols:**

```
ffffffff8107c4c0-ffffffff8107c531: intel_epb_offline (STB_LOCAL)
ffffffff821abb8d-ffffffff821abba9: intel_epb_offline.cold (STB_LOCAL)
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
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a490)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104a490-ffffffff8104a4c8: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039b60)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff81039b60-ffffffff81039bc2: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a2d0)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104a2d0-ffffffff8104a308: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_epb_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104b6e0)
Location: arch/x86/kernel/cpu/intel_epb.c:185
Inline: False
```
**Symbols:**

```
ffffffff8104b6e0-ffffffff8104b718: intel_epb_offline (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
