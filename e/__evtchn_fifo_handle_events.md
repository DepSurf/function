# Function: <code>__evtchn_fifo_handle_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff814ca900)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_cpu_notification
```
**Symbols:**

```
ffffffff814ca900-ffffffff814caa99: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8151b460)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_cpu_notification
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8151b460-ffffffff8151b5f9: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81547930)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81547930-ffffffff81547ac9: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8155b6e0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8155b6e0-ffffffff8155b879: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff815bfa10)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff815bfa10-ffffffff815bfb9c: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff815f8100-ffffffff815f8271: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff815f87bc-ffffffff815f87cf: __evtchn_fifo_handle_events.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff816131c0-ffffffff81613340: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81613889-ffffffff8161389c: __evtchn_fifo_handle_events.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81646fd0-ffffffff8164715b: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81647686-ffffffff8164769a: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81669470-ffffffff816695fb: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81669b26-ffffffff81669b3a: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81719ac0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81719ac0-ffffffff81719b62: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81736d10)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81736d10-ffffffff81736db0: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8171a640-ffffffff8171a7dc: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81bf7050-ffffffff81bf7063: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81798dd0-ffffffff81799026: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81cf5e09-ffffffff81cf5e1d: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff818d1f90-ffffffff818d22b3: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81ebdeea-ffffffff81ebdf1c: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a23ae0)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81a23ae0-ffffffff81a23d91: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a6cfa0)
Location: drivers/xen/events/events_fifo.c:319
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81a6cfa0-ffffffff81a6d2c1: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81abf070)
Location: drivers/xen/events/events_fifo.c:317
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_percpu_deinit
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81abf070-ffffffff81abf33f: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffff800010833d88)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffff800010833d88-ffff800010833fb0: __evtchn_fifo_handle_events (STB_LOCAL)
```
</details>
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
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8162f2e0-ffffffff8162f46b: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff8162f996-ffffffff8162f9aa: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8165d2b0-ffffffff8165d43b: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff8165d966-ffffffff8165d97a: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __evtchn_fifo_handle_events(unsigned int cpu, bool drop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:327
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_cpu_dead
  - drivers/xen/events/events_fifo.c:evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff816778c0-ffffffff81677a4b: __evtchn_fifo_handle_events (STB_LOCAL)
ffffffff81677f76-ffffffff81677f8a: __evtchn_fifo_handle_events.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct evtchn_loop_ctrl *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>bool drop</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
