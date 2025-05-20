# Function: <code>domain_setup_mon_state</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810416a3)
Location: arch/x86/kernel/cpu/intel_rdt.c:413
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044b0a)
Location: arch/x86/kernel/cpu/intel_rdt.c:414
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046e1a)
Location: arch/x86/kernel/cpu/intel_rdt.c:483
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055e33)
Location: arch/x86/kernel/cpu/resctrl/core.c:516
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059062)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059932)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
int domain_setup_mon_state(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e9a0)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff8105e9a0-ffffffff8105eb8d: domain_setup_mon_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int domain_setup_mon_state(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cec0)
Location: arch/x86/kernel/cpu/resctrl/core.c:510
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
**Symbols:**

```
ffffffff8105cec0-ffffffff8105d0ad: domain_setup_mon_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d994)
Location: arch/x86/kernel/cpu/resctrl/core.c:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81067096)
Location: arch/x86/kernel/cpu/resctrl/core.c:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073dbd)
Location: arch/x86/kernel/cpu/resctrl/core.c:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089ff5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3331
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108d081)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3746
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81094411)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3884
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810594b2)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810496d2)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810598e2)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ad82)
Location: arch/x86/kernel/cpu/resctrl/core.c:508
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
</ul>
