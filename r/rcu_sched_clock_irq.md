# Function: <code>rcu_sched_clock_irq</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2169
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8111e623-ffffffff8111e9e0: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff8111d1e0-ffffffff8111d556: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112ab7d-ffffffff8112af3e: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811296e0-ffffffff81129aec: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137e70)
Location: kernel/rcu/tree.c:2490
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81137e70-ffffffff81137fa5: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811336e0)
Location: kernel/rcu/tree.c:2617
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff811336e0-ffffffff811337ec: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134220)
Location: kernel/rcu/tree.c:2634
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81134220-ffffffff811343c1: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2585
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81caf5d9-ffffffff81caf616: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811567f0-ffffffff81156a29: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2653
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81e6027d-ffffffff81e602ba: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff8117f850-ffffffff8117fb11: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2321
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8205a31d-ffffffff8205a35a: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811b9af0-ffffffff811b9fa4: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2214
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff820d8b30-ffffffff820d8b6d: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811cc340-ffffffff811cc7f4: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2269
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff821b4255-ffffffff821b426a: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811e0ec0-ffffffff811e1278: rcu_sched_clock_irq (STB_GLOBAL)
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
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190cd8)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffff800010190cd8-ffff800010191578: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03de8b8)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c03de8b8-c03df2c8: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ec190)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
c0000000001ec190-c0000000001ecbd8: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124274)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffe000124274-ffffffe0001249b6: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112315d-ffffffff8112351e: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff81121cc0-ffffffff811220cc: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff81115c35-ffffffff81115ff9: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff811142f0-ffffffff81114774: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112104d-ffffffff8112140e: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff8111fbb0-ffffffff8111ffbc: rcu_sched_clock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void rcu_sched_clock_irq(int user);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2231
Inline: False
Direct callers:
  - kernel/time/timer.c:update_process_times
```
**Symbols:**

```
ffffffff8112d52b-ffffffff8112da1b: rcu_sched_clock_irq.cold (STB_LOCAL)
ffffffff8112bd20-ffffffff8112c29f: rcu_sched_clock_irq (STB_GLOBAL)
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
