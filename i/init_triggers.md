# Function: <code>init_triggers</code>

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
In kernel/sched/psi.c (ffffffff810f675b)
Location: kernel/sched/psi.c:490
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
In kernel/sched/psi.c (ffffffff811024f9)
Location: kernel/sched/psi.c:491
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff8110d053)
Location: kernel/sched/psi.c:491
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff8110a776)
Location: kernel/sched/psi.c:490
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff8110c476)
Location: kernel/sched/psi.c:499
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
In kernel/sched/psi.c (ffffffff8112b25e)
Location: kernel/sched/psi.c:510
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/build_utility.c (ffffffff81143d65)
Location: kernel/sched/psi.c:496
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_triggers(struct psi_group *group, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811688a0)
Location: kernel/sched/psi.c:519
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
```
**Symbols:**

```
ffffffff811688a0-ffffffff81168990: init_triggers (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff80001016723c)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (c03b366c)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (c0000000001bed10)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (ffffffe00010933a)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (ffffffff810fb809)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (ffffffff810eba29)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (ffffffff810f89c9)
Location: kernel/sched/psi.c:491
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
In kernel/sched/psi.c (ffffffff81103b19)
Location: kernel/sched/psi.c:491
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
</ul>
