# Function: <code>ct_idle_enter</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ct_idle_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff820c0100)
Location: kernel/context_tracking.c:317
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:default_idle_call
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
**Symbols:**

```
ffffffff820c0100-ffffffff820c010f: ct_idle_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ct_idle_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff82141f80)
Location: kernel/context_tracking.c:317
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:default_idle_call
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
**Symbols:**

```
ffffffff82141f80-ffffffff82141f8f: ct_idle_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ct_idle_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/context_tracking.c (ffffffff822244e0)
Location: kernel/context_tracking.c:317
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:default_idle_call
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
**Symbols:**

```
ffffffff822244e0-ffffffff822244f6: ct_idle_enter (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
