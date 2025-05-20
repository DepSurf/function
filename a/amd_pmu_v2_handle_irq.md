# Function: <code>amd_pmu_v2_handle_irq</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_pmu_v2_handle_irq(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:916
Inline: False
```
**Symbols:**

```
ffffffff8100ae70-ffffffff8100b159: amd_pmu_v2_handle_irq (STB_LOCAL)
ffffffff81e44787-ffffffff81e447a0: amd_pmu_v2_handle_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int amd_pmu_v2_handle_irq(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:880
Inline: False
```
**Symbols:**

```
ffffffff8100cde0-ffffffff8100d0e2: amd_pmu_v2_handle_irq (STB_LOCAL)
ffffffff8205046e-ffffffff82050487: amd_pmu_v2_handle_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int amd_pmu_v2_handle_irq(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:880
Inline: False
```
**Symbols:**

```
ffffffff8100c5a0-ffffffff8100c8b5: amd_pmu_v2_handle_irq (STB_LOCAL)
ffffffff820ce8c3-ffffffff820ce8dc: amd_pmu_v2_handle_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int amd_pmu_v2_handle_irq(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:882
Inline: False
```
**Symbols:**

```
ffffffff81011d80-ffffffff810120fa: amd_pmu_v2_handle_irq (STB_LOCAL)
ffffffff821a90ff-ffffffff821a9137: amd_pmu_v2_handle_irq.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
