# Function: <code>tick_nohz_idle_stop_tick_protected</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a0d1)
Location: include/linux/tick.h:131
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
```
In kernel/sched/idle.c (ffffffff810c43c9)
Location: include/linux/tick.h:131
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a721)
Location: include/linux/tick.h:131
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
```
In kernel/sched/idle.c (ffffffff810cd689)
Location: include/linux/tick.h:131
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102c531)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
```
In kernel/sched/idle.c (ffffffff810d5a75)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cda1)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ee01)
Location: include/linux/tick.h:143
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102fc11)
Location: include/linux/tick.h:143
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030721)
Location: include/linux/tick.h:144
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
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
In arch/x86/xen/smp_pv.c (ffffffff810355dd)
Location: include/linux/tick.h:144
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_nohz_idle_stop_tick_protected();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8103b120)
Location: include/linux/tick.h:144
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
**Symbols:**

```
ffffffff8103b120-ffffffff8103b13d: tick_nohz_idle_stop_tick_protected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_nohz_idle_stop_tick_protected();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81043850)
Location: include/linux/tick.h:144
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
**Symbols:**

```
ffffffff81043850-ffffffff81043875: tick_nohz_idle_stop_tick_protected (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cf01)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cd61)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102db51)
Location: include/linux/tick.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
