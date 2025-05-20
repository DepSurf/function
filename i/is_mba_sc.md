# Function: <code>is_mba_sc</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81047040)
Location: arch/x86/kernel/cpu/intel_rdt.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff81047040-ffffffff8104705b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81056060)
Location: arch/x86/kernel/cpu/resctrl/core.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff81056060-ffffffff8105607b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059240)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff81059240-ffffffff8105925b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059b10)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff81059b10-ffffffff81059b2b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ee80)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff8105ee80-ffffffff8105ee9b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d3c0)
Location: arch/x86/kernel/cpu/resctrl/core.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff8105d3c0-ffffffff8105d3db: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105dcf0)
Location: arch/x86/kernel/cpu/resctrl/core.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff8105dcf0-ffffffff8105dd0b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_get_config
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff81c9c633-ffffffff81c9c669: is_mba_sc.cold (STB_LOCAL)
ffffffff81067410-ffffffff81067447: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_get_config
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff81e4b980-ffffffff81e4b9b6: is_mba_sc.cold (STB_LOCAL)
ffffffff810740a0-ffffffff810740e7: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff82053041-ffffffff82053077: is_mba_sc.cold (STB_LOCAL)
ffffffff81084320-ffffffff81084367: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff820d15e6-ffffffff820d161c: is_mba_sc.cold (STB_LOCAL)
ffffffff810868d0-ffffffff81086913: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/kernel/cpu/resctrl/core.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw
```
**Symbols:**

```
ffffffff821ac1d9-ffffffff821ac20f: is_mba_sc.cold (STB_LOCAL)
ffffffff8108d7f0-ffffffff8108d833: is_mba_sc (STB_GLOBAL)
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
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059690)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff81059690-ffffffff810596ab: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810498b0)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff810498b0-ffffffff810498cb: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059ac0)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff81059ac0-ffffffff81059adb: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105af60)
Location: arch/x86/kernel/cpu/resctrl/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel
```
**Symbols:**

```
ffffffff8105af60-ffffffff8105af7b: is_mba_sc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
