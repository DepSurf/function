# Function: <code>__check_limbo</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044250)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81044250-ffffffff81044319: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047a20)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81047a20-ffffffff81047ae9: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a110)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8104a110-ffffffff8104a1d7: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a490)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105a490-ffffffff8105a557: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105e033-ffffffff8105e041: __check_limbo.cold (STB_LOCAL)
ffffffff8105d780-ffffffff8105d844: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e030)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105e030-ffffffff8105e0fb: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063d90)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81063d90-ffffffff81063e5b: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810621c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff810621c0-ffffffff8106228b: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062820)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81062820-ffffffff810628f1: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c6c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8106c6c0-ffffffff8106c791: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079ab0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81079ab0-ffffffff81079b99: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108aa90)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8108aa90-ffffffff8108abc1: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108db30)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8108db30-ffffffff8108dc61: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094ec0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff81094ec0-ffffffff81094ff1: __check_limbo (STB_GLOBAL)
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
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dbb0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105dbb0-ffffffff8105dc7b: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104de10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8104de10-ffffffff8104df3b: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dfe0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105dfe0-ffffffff8105e0ab: __check_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __check_limbo(struct rdt_domain *d, bool force_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f500)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo
```
**Symbols:**

```
ffffffff8105f500-ffffffff8105f5cb: __check_limbo (STB_GLOBAL)
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
