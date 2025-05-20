# Function: <code>rdt_ctrl_update</code>

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
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041940)
Location: arch/x86/kernel/cpu/intel_rdt.c:338
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81041940-ffffffff810419b3: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044d90)
Location: arch/x86/kernel/cpu/intel_rdt.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff81044d90-ffffffff81044e06: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (0)
Location: arch/x86/kernel/cpu/intel_rdt.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
**Symbols:**

```
ffffffff8104728b-ffffffff810472a7: rdt_ctrl_update.cold.14 (STB_LOCAL)
ffffffff810470d0-ffffffff81047130: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81056297-ffffffff810562b3: rdt_ctrl_update.cold.15 (STB_LOCAL)
ffffffff810560f0-ffffffff81056150: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff8105947a-ffffffff81059499: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff810592c0-ffffffff8105931a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81059d4a-ffffffff81059d69: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff81059b90-ffffffff81059bea: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff8105f248-ffffffff8105f267: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff8105ef00-ffffffff8105ef5a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81bd64af-ffffffff81bd64ce: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff8105d440-ffffffff8105d49a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81bc8761-ffffffff81bc8780: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff8105dd70-ffffffff8105ddca: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
**Symbols:**

```
ffffffff81c9c696-ffffffff81c9c6ca: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff810674f0-ffffffff8106756b: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
**Symbols:**

```
ffffffff81e4b9e3-ffffffff81e4ba17: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff810741b0-ffffffff81074243: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
**Symbols:**

```
ffffffff82053077-ffffffff8205308c: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff81084400-ffffffff81084498: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:369
Inline: False
```
**Symbols:**

```
ffffffff820d161c-ffffffff820d1631: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff810869b0-ffffffff81086a48: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:373
Inline: False
```
**Symbols:**

```
ffffffff821ac20f-ffffffff821ac224: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff8108d8d0-ffffffff8108d968: rdt_ctrl_update (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff810598ca-ffffffff810598e9: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff81059710-ffffffff8105976a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81049a55-ffffffff81049a74: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff81049930-ffffffff8104998a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff81059cfa-ffffffff81059d19: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff81059b40-ffffffff81059b9a: rdt_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void rdt_ctrl_update(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
**Symbols:**

```
ffffffff8105b19a-ffffffff8105b1b9: rdt_ctrl_update.cold (STB_LOCAL)
ffffffff8105afe0-ffffffff8105b03a: rdt_ctrl_update (STB_GLOBAL)
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
