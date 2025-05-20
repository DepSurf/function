# Function: <code>cqm_handle_limbo</code>

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
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044440)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:325
Inline: False
```
**Symbols:**

```
ffffffff81044440-ffffffff810444ea: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047c10)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:325
Inline: False
```
**Symbols:**

```
ffffffff81047c10-ffffffff81047cba: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:478
Inline: False
```
**Symbols:**

```
ffffffff8104a986-ffffffff8104a99e: cqm_handle_limbo.cold.9 (STB_LOCAL)
ffffffff8104a300-ffffffff8104a39d: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:475
Inline: False
```
**Symbols:**

```
ffffffff8105ad06-ffffffff8105ad1e: cqm_handle_limbo.cold.10 (STB_LOCAL)
ffffffff8105a680-ffffffff8105a71d: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8105e041-ffffffff8105e059: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8105d970-ffffffff8105da10: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8105e8d9-ffffffff8105e8f1: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8105e220-ffffffff8105e2c0: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:471
Inline: False
```
**Symbols:**

```
ffffffff81064375-ffffffff8106438d: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff81063fe0-ffffffff81064080: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062410)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:532
Inline: False
```
**Symbols:**

```
ffffffff81062410-ffffffff8106248c: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062a30)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:531
Inline: False
```
**Symbols:**

```
ffffffff81062a30-ffffffff81062aa9: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c8c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:546
Inline: False
```
**Symbols:**

```
ffffffff8106c8c0-ffffffff8106c939: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079d00)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:546
Inline: False
```
**Symbols:**

```
ffffffff81079d00-ffffffff81079d83: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ad70)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:627
Inline: False
```
**Symbols:**

```
ffffffff8108ad70-ffffffff8108adf3: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108de10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:639
Inline: False
```
**Symbols:**

```
ffffffff8108de10-ffffffff8108de93: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810951a0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:639
Inline: False
```
**Symbols:**

```
ffffffff810951a0-ffffffff81095223: cqm_handle_limbo (STB_GLOBAL)
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
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8105e459-ffffffff8105e471: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8105dda0-ffffffff8105de40: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8104e789-ffffffff8104e7a1: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8104e060-ffffffff8104e100: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8105e889-ffffffff8105e8a1: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8105e1d0-ffffffff8105e270: cqm_handle_limbo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cqm_handle_limbo(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:470
Inline: False
```
**Symbols:**

```
ffffffff8105fdc9-ffffffff8105fde1: cqm_handle_limbo.cold (STB_LOCAL)
ffffffff8105f6f0-ffffffff8105f790: cqm_handle_limbo (STB_GLOBAL)
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
