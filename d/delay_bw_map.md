# Function: <code>delay_bw_map</code>

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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810410f3)
Location: arch/x86/kernel/cpu/intel_rdt.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810444e3)
Location: arch/x86/kernel/cpu/intel_rdt.c:298
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046b26)
Location: arch/x86/kernel/cpu/intel_rdt.c:352
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8104726b-ffffffff8104728b: delay_bw_map.cold.13 (STB_LOCAL)
ffffffff81047060-ffffffff8104708e: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055ac6)
Location: arch/x86/kernel/cpu/resctrl/core.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81056277-ffffffff81056297: delay_bw_map.cold.14 (STB_LOCAL)
ffffffff81056080-ffffffff810560ae: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058d36)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105945a-ffffffff8105947a: delay_bw_map.cold (STB_LOCAL)
ffffffff81059260-ffffffff8105928e: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059606)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81059d2a-ffffffff81059d4a: delay_bw_map.cold (STB_LOCAL)
ffffffff81059b30-ffffffff81059b5e: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e976)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff8105f228-ffffffff8105f248: delay_bw_map.cold (STB_LOCAL)
ffffffff8105eea0-ffffffff8105eece: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ce96)
Location: arch/x86/kernel/cpu/resctrl/core.c:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81bd648f-ffffffff81bd64af: delay_bw_map.cold (STB_LOCAL)
ffffffff8105d3e0-ffffffff8105d40e: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d802)
Location: arch/x86/kernel/cpu/resctrl/core.c:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81bc873c-ffffffff81bc8761: delay_bw_map.cold (STB_LOCAL)
ffffffff8105dd10-ffffffff8105dd35: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066ec3)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81c9c669-ffffffff81c9c696: delay_bw_map.cold (STB_LOCAL)
ffffffff81067450-ffffffff81067492: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073752)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw
```
**Symbols:**

```
ffffffff81e4b9b6-ffffffff81e4b9e3: delay_bw_map.cold (STB_LOCAL)
ffffffff810740f0-ffffffff81074142: delay_bw_map (STB_GLOBAL)
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083a6e)
Location: arch/x86/kernel/cpu/resctrl/core.c:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81085f2a)
Location: arch/x86/kernel/cpu/resctrl/core.c:318
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108ceca)
Location: arch/x86/kernel/cpu/resctrl/core.c:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059186)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff810598aa-ffffffff810598ca: delay_bw_map.cold (STB_LOCAL)
ffffffff810596b0-ffffffff810596de: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049464)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81049a35-ffffffff81049a55: delay_bw_map.cold (STB_LOCAL)
ffffffff810498d0-ffffffff810498fe: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810595b6)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff81059cda-ffffffff81059cfa: delay_bw_map.cold (STB_LOCAL)
ffffffff81059ae0-ffffffff81059b0e: delay_bw_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105aa56)
Location: arch/x86/kernel/cpu/resctrl/core.c:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
  - arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow
```
**Symbols:**

```
ffffffff8105b17a-ffffffff8105b19a: delay_bw_map.cold (STB_LOCAL)
ffffffff8105af80-ffffffff8105afae: delay_bw_map (STB_GLOBAL)
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
