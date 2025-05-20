# Function: <code>detect_tme</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104512b)
Location: arch/x86/kernel/cpu/intel.c:527
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81046b3f)
Location: arch/x86/kernel/cpu/intel.c:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049636)
Location: arch/x86/kernel/cpu/intel.c:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049ef7)
Location: arch/x86/kernel/cpu/intel.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:511
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104dc70-ffffffff8104dd68: detect_tme (STB_LOCAL)
ffffffff8104e687-ffffffff8104e782: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104d1a0-ffffffff8104d298: detect_tme (STB_LOCAL)
ffffffff81bd51f2-ffffffff81bd52ed: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104ed20-ffffffff8104ee18: detect_tme (STB_LOCAL)
ffffffff81bc75fa-ffffffff81bc76f5: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81056db0-ffffffff81056f08: detect_tme (STB_LOCAL)
ffffffff81c9af02-ffffffff81c9b086: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:550
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff810630c0-ffffffff81063253: detect_tme (STB_LOCAL)
ffffffff81e4a439-ffffffff81e4a5bd: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81071fd0-ffffffff81072242: detect_tme (STB_LOCAL)
ffffffff82052ac3-ffffffff82052b40: detect_tme.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void detect_tme(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81073bc0-ffffffff81073e2e: detect_tme (STB_LOCAL)
ffffffff820d0f90-ffffffff820d100d: detect_tme.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a067)
Location: arch/x86/kernel/cpu/intel.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81039303)
Location: arch/x86/kernel/cpu/intel.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049ea7)
Location: arch/x86/kernel/cpu/intel.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b2b7)
Location: arch/x86/kernel/cpu/intel.c:563
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
