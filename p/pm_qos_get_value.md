# Function: <code>pm_qos_get_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810cbffd)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d0c73)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d76e3)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6733)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
**Symbols:**

```
ffffffff810d715b-ffffffff810d7161: pm_qos_get_value.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810de6c3)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
**Symbols:**

```
ffffffff810df0fd-ffffffff810df103: pm_qos_get_value.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810e6d12)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
**Symbols:**

```
ffffffff810e6ae0-ffffffff810e6ae6: pm_qos_get_value.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810f2312)
Location: kernel/power/qos.c:149
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff810f20e0-ffffffff810f20e6: pm_qos_get_value.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810fa7c5)
Location: kernel/power/qos.c:150
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff810fa5c0-ffffffff810fa5c2: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff81106665)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff811063a0-ffffffff811063a2: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pm_qos_get_value(struct pm_qos_constraints *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111360)
Location: kernel/power/qos.c:58
Inline: True
Direct callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
**Symbols:**

```
ffffffff81111360-ffffffff811113ad: pm_qos_get_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pm_qos_get_value(struct pm_qos_constraints *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e4e0)
Location: kernel/power/qos.c:58
Inline: True
Direct callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
**Symbols:**

```
ffffffff8110e4e0-ffffffff8110e52d: pm_qos_get_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pm_qos_get_value(struct pm_qos_constraints *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110efc0)
Location: kernel/power/qos.c:58
Inline: True
Direct callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
**Symbols:**

```
ffffffff8110efc0-ffffffff8110f00d: pm_qos_get_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112e8b8)
Location: kernel/power/qos.c:58
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fcee)
Location: kernel/power/qos.c:58
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
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
In kernel/power/qos.c (ffffffff8117e59e)
Location: kernel/power/qos.c:58
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
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
In kernel/power/qos.c (ffffffff8118f1fe)
Location: kernel/power/qos.c:58
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
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
In kernel/power/qos.c (ffffffff8119dbae)
Location: kernel/power/qos.c:58
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffff80001016cdb8)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffff80001016cbb8-ffff80001016cbbc: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (c03b818c)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
c03b7df0-c03b7e00: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (c0000000001c4740)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
c0000000001c4210-c0000000001c4214: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffe00010ca5c)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffe00010c734-ffffffe00010c73c: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810ff975)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff810ff6b0-ffffffff810ff6b2: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810efb65)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff810ef8a0-ffffffff810ef8a2: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff810fcb35)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff810fc870-ffffffff810fc872: pm_qos_get_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff81107d65)
Location: kernel/power/qos.c:102
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
Direct callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
**Symbols:**

```
ffffffff81107aa0-ffffffff81107aa2: pm_qos_get_value.part.0 (STB_LOCAL)
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
</ul>
