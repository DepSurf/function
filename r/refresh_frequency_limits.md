# Function: <code>refresh_frequency_limits</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81891630)
Location: drivers/cpufreq/cpufreq.c:1106
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81891630-ffffffff818916b6: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff818916c0-ffffffff818916f2: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c3800)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818c3800-ffffffff818c385b: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995d6b)
Location: drivers/cpufreq/cpufreq.c:1130
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81995c00-ffffffff81995c43: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff81995c50-ffffffff81995c82: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998c59)
Location: drivers/cpufreq/cpufreq.c:1134
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81998ac0-ffffffff81998b03: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff81998b10-ffffffff81998b42: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d6fb)
Location: drivers/cpufreq/cpufreq.c:1131
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8197d590-ffffffff8197d5d3: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff8197d5e0-ffffffff8197d612: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a26788)
Location: drivers/cpufreq/cpufreq.c:1131
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81a26620-ffffffff81a26660: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff81a26660-ffffffff81a26692: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b90468)
Location: drivers/cpufreq/cpufreq.c:1136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81b902d0-ffffffff81b90318: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff81b90320-ffffffff81b9035d: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d30638)
Location: drivers/cpufreq/cpufreq.c:1127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d30440-ffffffff81d30488: refresh_frequency_limits.part.0 (STB_LOCAL)
ffffffff81d304a0-ffffffff81d304dd: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d99720)
Location: drivers/cpufreq/cpufreq.c:1134
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d99720-ffffffff81d99780: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e51390)
Location: drivers/cpufreq/cpufreq.c:1175
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_notify_work
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81e51390-ffffffff81e513f0: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b211c8)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
```
**Symbols:**

```
ffff800010b211c8-ffff800010b21238: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfb948)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
```
**Symbols:**

```
c0bfb858-c0bfb8b4: refresh_frequency_limits.part.0 (STB_LOCAL)
c0bfb8b4-c0bfb8dc: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14f20)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
```
**Symbols:**

```
c000000000c14f20-c000000000c14fd4: refresh_frequency_limits (STB_GLOBAL)
```
</details>
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
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867f20)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81867f20-ffffffff81867f7b: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81830bd0)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81830bd0-ffffffff81830c2b: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8cb0)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818b8cb0-ffffffff818b8d0b: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void refresh_frequency_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4f90)
Location: drivers/cpufreq/cpufreq.c:1113
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff818d4f90-ffffffff818d4feb: refresh_frequency_limits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
