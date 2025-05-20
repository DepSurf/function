# Function: <code>cpu_stop_queue_two_works</code>

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
In kernel/stop_machine.c (ffffffff811204fb)
Location: kernel/stop_machine.c:219
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff8112845a)
Location: kernel/stop_machine.c:227
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff811320eb)
Location: kernel/stop_machine.c:227
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff811336a9)
Location: kernel/stop_machine.c:227
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81140459)
Location: kernel/stop_machine.c:227
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114ed85)
Location: kernel/stop_machine.c:234
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115ba65)
Location: kernel/stop_machine.c:234
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81168138)
Location: kernel/stop_machine.c:242
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff81173ff8)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81185b60)
Location: kernel/stop_machine.c:245
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff81185b60-ffffffff81185cc5: cpu_stop_queue_two_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81182c90)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff81182c90-ffffffff81182df5: cpu_stop_queue_two_works (STB_LOCAL)
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
In kernel/stop_machine.c (ffffffff81184192)
Location: kernel/stop_machine.c:261
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff811abf90-ffffffff811ac15d: cpu_stop_queue_two_works (STB_LOCAL)
ffffffff81cb33bf-ffffffff81cb342b: cpu_stop_queue_two_works.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff811dd410-ffffffff811dd653: cpu_stop_queue_two_works (STB_LOCAL)
ffffffff81e6417f-ffffffff81e6422b: cpu_stop_queue_two_works.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff81222e40-ffffffff81223083: cpu_stop_queue_two_works (STB_LOCAL)
ffffffff8205c4b5-ffffffff8205c561: cpu_stop_queue_two_works.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff81239510-ffffffff81239753: cpu_stop_queue_two_works (STB_LOCAL)
ffffffff820dae12-ffffffff820daebe: cpu_stop_queue_two_works.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpu_stop_queue_two_works(int cpu1, struct cpu_stop_work *work1, int cpu2, struct cpu_stop_work *work2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:261
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_two_cpus
```
**Symbols:**

```
ffffffff812531e0-ffffffff81253423: cpu_stop_queue_two_works (STB_LOCAL)
ffffffff821b6b10-ffffffff821b6bbc: cpu_stop_queue_two_works.cold (STB_LOCAL)
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
In kernel/stop_machine.c (ffff8000101e87d8)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (c04288c8)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (c0000000002591f0)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffe00015d7ac)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff8116c618)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff8115f7e8)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff8116a3e8)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
In kernel/stop_machine.c (ffffffff81177b36)
Location: kernel/stop_machine.c:244
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_two_cpus
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
