# Function: <code>mbm_update</code>

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
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810441d0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff810441d0-ffffffff8104424c: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810479a0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff810479a0-ffffffff81047a1c: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81049fe0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:444
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81049fe0-ffffffff8104a104: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a360)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105a360-ffffffff8105a484: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d650)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105d650-ffffffff8105d77b: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df00)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105df00-ffffffff8105e02b: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063bd0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81063bd0-ffffffff81063c6d: mbm_update.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061ff0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:498
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81061ff0-ffffffff81062092: mbm_update.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810626e0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:497
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff810626e0-ffffffff81062811: mbm_update.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:512
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8106c560-ffffffff8106c6b2: mbm_update.constprop.0 (STB_LOCAL)
ffffffff81c9cca7-ffffffff81c9ccbc: mbm_update.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:512
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81079940-ffffffff81079aa9: mbm_update.constprop.0 (STB_LOCAL)
ffffffff81e4c000-ffffffff81e4c015: mbm_update.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:591
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8108a950-ffffffff8108aa75: mbm_update.constprop.0 (STB_LOCAL)
ffffffff82053664-ffffffff82053679: mbm_update.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:603
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8108d9f0-ffffffff8108db15: mbm_update.constprop.0 (STB_LOCAL)
ffffffff820d1c57-ffffffff820d1c6c: mbm_update.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:603
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81094d80-ffffffff81094ea5: mbm_update.constprop.0 (STB_LOCAL)
ffffffff821ac8bb-ffffffff821ac8d0: mbm_update.constprop.0.cold (STB_LOCAL)
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
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105da80)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105da80-ffffffff8105dbab: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dc80)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8104dc80-ffffffff8104de04: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105deb0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105deb0-ffffffff8105dfdb: mbm_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mbm_update(struct rdt_domain *d, int rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f3d0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105f3d0-ffffffff8105f4fb: mbm_update (STB_LOCAL)
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
