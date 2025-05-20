# Function: <code>dyn_constraint</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c0c0)
Location: arch/x86/events/intel/core.c:2805
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100c0c0-ffffffff8100c116: dyn_constraint.isra.16 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100c860)
Location: arch/x86/events/intel/core.c:2886
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100c860-ffffffff8100c8b6: dyn_constraint.isra.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100cc90)
Location: arch/x86/events/intel/core.c:2887
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100cc90-ffffffff8100cce6: dyn_constraint.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct event_constraint *dyn_constraint(struct cpu_hw_events *cpuc, struct event_constraint *c, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d180)
Location: arch/x86/events/intel/core.c:2906
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100d180-ffffffff8100d1dd: dyn_constraint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct event_constraint *dyn_constraint(struct cpu_hw_events *cpuc, struct event_constraint *c, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c140)
Location: arch/x86/events/intel/core.c:3193
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100c140-ffffffff8100c19d: dyn_constraint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct event_constraint *dyn_constraint(struct cpu_hw_events *cpuc, struct event_constraint *c, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c8c0)
Location: arch/x86/events/intel/core.c:3303
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100c8c0-ffffffff8100c91d: dyn_constraint (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff81010be6)
Location: arch/x86/events/intel/core.c:3310
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
In arch/x86/events/intel/core.c (ffffffff810122c5)
Location: arch/x86/events/intel/core.c:3372
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
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
In arch/x86/events/intel/core.c (ffffffff81016215)
Location: arch/x86/events/intel/core.c:3445
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
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
In arch/x86/events/intel/core.c (ffffffff81015a95)
Location: arch/x86/events/intel/core.c:3463
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
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
In arch/x86/events/intel/core.c (ffffffff8101b575)
Location: arch/x86/events/intel/core.c:3471
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_excl_constraints
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cc90)
Location: arch/x86/events/intel/core.c:2887
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100cc90-ffffffff8100cce6: dyn_constraint.isra.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100b490)
Location: arch/x86/events/intel/core.c:2887
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100b490-ffffffff8100b4e6: dyn_constraint.isra.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100cc50)
Location: arch/x86/events/intel/core.c:2887
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100cc50-ffffffff8100cca6: dyn_constraint.isra.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100ce80)
Location: arch/x86/events/intel/core.c:2887
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
**Symbols:**

```
ffffffff8100ce80-ffffffff8100ced6: dyn_constraint.isra.0 (STB_LOCAL)
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
