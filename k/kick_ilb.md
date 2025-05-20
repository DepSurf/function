# Function: <code>kick_ilb</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4bd0)
Location: kernel/sched/fair.c:9344
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810c4bd0-ffffffff810c4c5e: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdfa0)
Location: kernel/sched/fair.c:9447
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810cdfa0-ffffffff810ce02e: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d63a0)
Location: kernel/sched/fair.c:9364
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810d63a0-ffffffff810d643d: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0aa0)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810e0aa0-ffffffff810e0b3d: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8f90)
Location: kernel/sched/fair.c:10026
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff810e8f90-ffffffff810e9044: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6d40)
Location: kernel/sched/fair.c:10140
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff810e6d40-ffffffff810e6dfe: kick_ilb (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f68f8)
Location: kernel/sched/fair.c:10179
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
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
In kernel/sched/fair.c (ffffffff81110791)
Location: kernel/sched/fair.c:10421
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
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
In kernel/sched/fair.c (ffffffff8112c8fa)
Location: kernel/sched/fair.c:10523
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
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
In kernel/sched/fair.c (ffffffff811565dc)
Location: kernel/sched/fair.c:11051
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81153800)
Location: kernel/sched/fair.c:11351
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff81153800-ffffffff81153938: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115f890)
Location: kernel/sched/fair.c:11817
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff8115f890-ffffffff8115f9bc: kick_ilb (STB_LOCAL)
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
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101423f8)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffff8000101423f8-ffff8000101424dc: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0390f80)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
c0390f80-c039104c: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000190990)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
c000000000190990-c000000000190adc: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000eee88)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffe0000eee88-ffffffe0000eef42: kick_ilb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dac50)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810dac50-ffffffff810daced: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9c60)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810c9c60-ffffffff810c9cfd: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6fd0)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810d6fd0-ffffffff810d706d: kick_ilb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2980)
Location: kernel/sched/fair.c:9348
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810e2980-ffffffff810e2a1d: kick_ilb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
