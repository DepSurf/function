# Function: <code>domain_add_cpu</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810431d3)
Location: arch/x86/kernel/cpu/intel_rdt.c:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810414e6)
Location: arch/x86/kernel/cpu/intel_rdt.c:464
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044946)
Location: arch/x86/kernel/cpu/intel_rdt.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046c17)
Location: arch/x86/kernel/cpu/intel_rdt.c:534
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055c26)
Location: arch/x86/kernel/cpu/resctrl/core.c:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058e96)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059766)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105eb90)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff8105eb90-ffffffff8105edc8: domain_add_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d0b0)
Location: arch/x86/kernel/cpu/resctrl/core.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff8105d0b0-ffffffff8105d30e: domain_add_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d820)
Location: arch/x86/kernel/cpu/resctrl/core.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff8105d820-ffffffff8105dc34: domain_add_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:499
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81066ef0-ffffffff81067360: domain_add_cpu (STB_LOCAL)
ffffffff81c9c5f5-ffffffff81c9c633: domain_add_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:499
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81073b50-ffffffff81073fd5: domain_add_cpu (STB_LOCAL)
ffffffff81e4b942-ffffffff81e4b980: domain_add_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff81083f00-ffffffff8108423b: domain_add_cpu (STB_LOCAL)
ffffffff82053003-ffffffff82053041: domain_add_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff810864a0-ffffffff810867f0: domain_add_cpu (STB_LOCAL)
ffffffff820d15a8-ffffffff820d15e6: domain_add_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void domain_add_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
**Symbols:**

```
ffffffff8108d380-ffffffff8108d705: domain_add_cpu (STB_LOCAL)
ffffffff821ac19b-ffffffff821ac1d9: domain_add_cpu.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810592e6)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049506)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059716)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105abb6)
Location: arch/x86/kernel/cpu/resctrl/core.c:557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
