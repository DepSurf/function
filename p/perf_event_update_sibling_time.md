# Function: <code>perf_event_update_sibling_time</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7652)
Location: kernel/events/core.c:647
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
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
In kernel/events/core.c (ffffffff811d7068)
Location: kernel/events/core.c:647
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff811d47b0-ffffffff811d47dc: perf_event_update_sibling_time.part.74 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811e7498)
Location: kernel/events/core.c:647
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff811e4470-ffffffff811e449c: perf_event_update_sibling_time.part.44 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811feacc)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff811fb760-ffffffff811fb791: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120bb2c)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff81208b10-ffffffff81208b41: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81234e8a)
Location: kernel/events/core.c:654
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff81233240-ffffffff812332e5: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8123f2da)
Location: kernel/events/core.c:658
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff8123d010-ffffffff8123d0b5: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff812434aa)
Location: kernel/events/core.c:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_set_state
  - kernel/events/core.c:perf_event_set_state
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff81241a90-ffffffff81241b49: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8128a28a)
Location: kernel/events/core.c:657
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_del_event
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
In kernel/events/core.c (ffffffff812dec95)
Location: kernel/events/core.c:656
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
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
In kernel/events/core.c (ffffffff81346e94)
Location: kernel/events/core.c:650
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
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
In kernel/events/core.c (ffffffff81377fc1)
Location: kernel/events/core.c:650
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
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
In kernel/events/core.c (ffffffff813a12a1)
Location: kernel/events/core.c:651
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
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
In kernel/events/core.c (ffff800010295b2c)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffff800010292318-ffff800010292358: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (c04c5bf8)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
c04c36cc-c04c3704: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (c000000000343404)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
c0000000003406c0-c000000000340720: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001c6a6e)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffe0001c4834-ffffffe0001c4868: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120414c)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff81201130-ffffffff81201161: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811f6edc)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff811f3e80-ffffffff811f3eb1: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81201f1c)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff811fef00-ffffffff811fef31: perf_event_update_sibling_time.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81211726)
Location: kernel/events/core.c:648
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
Direct callers:
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
```
**Symbols:**

```
ffffffff8120df90-ffffffff8120dfc1: perf_event_update_sibling_time.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
