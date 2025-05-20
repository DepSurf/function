# Function: <code>has_busy_rmid</code>

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
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044481)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff81044320-ffffffff81044353: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047c51)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff81047af0-ffffffff81047b23: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a341)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff8104a1e0-ffffffff8104a213: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a6c1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:147
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105a560-ffffffff8105a593: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d9b1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105d850-ffffffff8105d883: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e261)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105e100-ffffffff8105e133: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81064021)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81063e60-ffffffff81063e96: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062443)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81062290-ffffffff810622c6: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062a63)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81062900-ffffffff81062936: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c8f3)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff8106c7a0-ffffffff8106c7d0: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079d31)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81079ba0-ffffffff81079bda: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ada1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
**Symbols:**

```
ffffffff8108abe0-ffffffff8108ac1a: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108de41)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
**Symbols:**

```
ffffffff8108dc80-ffffffff8108dcba: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810951d1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
**Symbols:**

```
ffffffff81095010-ffffffff8109504a: has_busy_rmid (STB_GLOBAL)
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
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dde1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105dc80-ffffffff8105dcb3: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e0a1)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8104df40-ffffffff8104df73: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e211)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105e0b0-ffffffff8105e0e3: has_busy_rmid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool has_busy_rmid(struct rdt_resource *r, struct rdt_domain *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f731)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105f5d0-ffffffff8105f603: has_busy_rmid (STB_GLOBAL)
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
