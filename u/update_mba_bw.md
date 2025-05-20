# Function: <code>update_mba_bw</code>

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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a5f6)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a976)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:361
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dc65)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e525)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81063730-ffffffff810638e5: update_mba_bw (STB_LOCAL)
ffffffff8106435d-ffffffff81064375: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81061b50-ffffffff81061d02: update_mba_bw (STB_LOCAL)
ffffffff81bd6517-ffffffff81bd652f: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81062320-ffffffff810624d2: update_mba_bw (STB_LOCAL)
ffffffff81bc87c9-ffffffff81bc87e1: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8106c170-ffffffff8106c34e: update_mba_bw (STB_LOCAL)
ffffffff81c9cc60-ffffffff81c9cc8c: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff810794e0-ffffffff8107970a: update_mba_bw (STB_LOCAL)
ffffffff81e4bfb9-ffffffff81e4bfe5: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8108a290-ffffffff8108a471: update_mba_bw (STB_LOCAL)
ffffffff820535d4-ffffffff820535e8: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8108d300-ffffffff8108d4e1: update_mba_bw (STB_LOCAL)
ffffffff820d1be6-ffffffff820d1bfa: update_mba_bw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_mba_bw(struct rdtgroup *rgrp, struct rdt_domain *dom_mbm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81094690-ffffffff81094871: update_mba_bw (STB_LOCAL)
ffffffff821ac84a-ffffffff821ac85e: update_mba_bw.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e0a5)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e3b5)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e4d5)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fa15)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
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
