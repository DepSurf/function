# Function: <code>get_domain_from_cpu</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041957)
Location: arch/x86/kernel/cpu/intel_rdt.c:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81041900-ffffffff81041934: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044da7)
Location: arch/x86/kernel/cpu/intel_rdt.c:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81044d50-ffffffff81044d87: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810470e0)
Location: arch/x86/kernel/cpu/intel_rdt.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81047090-ffffffff810470c7: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81056103)
Location: arch/x86/kernel/cpu/resctrl/core.c:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff810560b0-ffffffff810560e7: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810592d4)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81059290-ffffffff810592bf: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059ba4)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81059b60-ffffffff81059b8f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ef14)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff8105eed0-ffffffff8105eeff: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d454)
Location: arch/x86/kernel/cpu/resctrl/core.c:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff8105d410-ffffffff8105d43f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105dd84)
Location: arch/x86/kernel/cpu/resctrl/core.c:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff8105dd40-ffffffff8105dd6f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8106750c)
Location: arch/x86/kernel/cpu/resctrl/core.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff810674a0-ffffffff810674cf: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810741cc)
Location: arch/x86/kernel/cpu/resctrl/core.c:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81074150-ffffffff8107418f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108441c)
Location: arch/x86/kernel/cpu/resctrl/core.c:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81084380-ffffffff810843bf: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810869cc)
Location: arch/x86/kernel/cpu/resctrl/core.c:351
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81086930-ffffffff8108696f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d8ec)
Location: arch/x86/kernel/cpu/resctrl/core.c:355
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff8108d850-ffffffff8108d88f: get_domain_from_cpu (STB_GLOBAL)
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
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059724)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff810596e0-ffffffff8105970f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049944)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81049900-ffffffff8104992f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059b54)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81059b10-ffffffff81059b3f: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rdt_domain *get_domain_from_cpu(int cpu, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105aff4)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105afb0-ffffffff8105afdf: get_domain_from_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
