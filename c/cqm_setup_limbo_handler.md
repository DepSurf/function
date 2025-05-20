# Function: <code>cqm_setup_limbo_handler</code>

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
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810444f0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
```
**Symbols:**

```
ffffffff810444f0-ffffffff8104453b: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047cc0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
```
**Symbols:**

```
ffffffff81047cc0-ffffffff81047d0b: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a3a0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8104a3a0-ffffffff8104a3eb: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a720)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105a720-ffffffff8105a76b: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105da10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105da10-ffffffff8105da5d: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e2c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105e2c0-ffffffff8105e30d: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063d12)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:497
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81064080-ffffffff810640cd: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062142)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81062490-ffffffff810624dd: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062ab0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:551
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff81062ab0-ffffffff81062afb: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c940)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff8106c940-ffffffff8106c98b: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079d90)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff81079d90-ffffffff81079de9: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ae10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff8108ae10-ffffffff8108ae69: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108deb0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff8108deb0-ffffffff8108df09: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81095240)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
**Symbols:**

```
ffffffff81095240-ffffffff81095299: cqm_setup_limbo_handler (STB_GLOBAL)
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
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105de40)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105de40-ffffffff8105de8d: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e100)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8104e100-ffffffff8104e14d: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e270)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105e270-ffffffff8105e2bd: cqm_setup_limbo_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cqm_setup_limbo_handler(struct rdt_domain *dom, long unsigned int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f790)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8105f790-ffffffff8105f7dd: cqm_setup_limbo_handler (STB_GLOBAL)
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
