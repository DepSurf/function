# Function: <code>update_triggers</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f667a)
Location: kernel/sched/psi.c:502
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff8110241a)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 update_triggers(struct psi_group *group, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c700)
Location: kernel/sched/psi.c:503
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff8110c700-ffffffff8110c82b: update_triggers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 update_triggers(struct psi_group *group, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81109920)
Location: kernel/sched/psi.c:502
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff81109920-ffffffff81109a4b: update_triggers (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff8110c33a)
Location: kernel/sched/psi.c:511
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/psi.c (ffffffff8112b11a)
Location: kernel/sched/psi.c:522
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 update_triggers(struct psi_group *group, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:508
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
```
**Symbols:**

```
ffffffff8113e390-ffffffff8113e548: update_triggers (STB_LOCAL)
ffffffff81e56c2a-ffffffff81e56c60: update_triggers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 update_triggers(struct psi_group *group, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:531
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
```
**Symbols:**

```
ffffffff811689a0-ffffffff81168ba5: update_triggers (STB_LOCAL)
ffffffff82057bdc-ffffffff82057c3b: update_triggers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 update_triggers(struct psi_group *group, u64 now, bool *update_total, enum psi_aggregators aggregator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:437
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff81178f60-ffffffff81179155: update_triggers (STB_LOCAL)
ffffffff820d63cd-ffffffff820d6443: update_triggers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_triggers(struct psi_group *group, u64 now, enum psi_aggregators aggregator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:437
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8118dd00-ffffffff8118def7: update_triggers (STB_LOCAL)
ffffffff821b17ca-ffffffff821b1829: update_triggers.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167108)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b3430)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bebc4)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe00010927e)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
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
In kernel/sched/psi.c (ffffffff810fb72a)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eb94a)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f88ea)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff81103a3a)
Location: kernel/sched/psi.c:503
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *update_total</code>
</li>
<li>
<b>Param added. </b>
<code>enum psi_aggregators aggregator</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *update_total</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, now, update_total, aggregator</code> ➡️ <code>group, now, aggregator</code>
</li>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
