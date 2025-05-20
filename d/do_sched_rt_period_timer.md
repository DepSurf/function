# Function: <code>do_sched_rt_period_timer</code>

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
In kernel/sched/rt.c (ffffffff810bfc68)
Location: kernel/sched/rt.c:811
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810c3610)
Location: kernel/sched/rt.c:819
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810c9670)
Location: kernel/sched/rt.c:819
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810c35d8)
Location: kernel/sched/rt.c:820
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810cadf5)
Location: kernel/sched/rt.c:810
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810d39c5)
Location: kernel/sched/rt.c:809
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810dd3a5)
Location: kernel/sched/rt.c:811
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e4380)
Location: kernel/sched/rt.c:811
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810eef05)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8680)
Location: kernel/sched/rt.c:853
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810f8680-ffffffff810f893a: do_sched_rt_period_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f6890)
Location: kernel/sched/rt.c:854
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810f6890-ffffffff810f6b4e: do_sched_rt_period_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8c20)
Location: kernel/sched/rt.c:854
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff810f8c20-ffffffff810f8ede: do_sched_rt_period_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff811140f0)
Location: kernel/sched/rt.c:865
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff811140f0-ffffffff811143cf: do_sched_rt_period_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:901
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff81131440-ffffffff811317be: do_sched_rt_period_timer (STB_LOCAL)
ffffffff81e560e4-ffffffff81e56101: do_sched_rt_period_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:901
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff8115b430-ffffffff8115b7ba: do_sched_rt_period_timer (STB_LOCAL)
ffffffff82057315-ffffffff82057332: do_sched_rt_period_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:901
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff8116b610-ffffffff8116b99c: do_sched_rt_period_timer (STB_LOCAL)
ffffffff820d5b3d-ffffffff820d5b58: do_sched_rt_period_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_sched_rt_period_timer(struct rt_bandwidth *rt_b, int overrun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:857
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
**Symbols:**

```
ffffffff81178f10-ffffffff8117929c: do_sched_rt_period_timer (STB_LOCAL)
ffffffff821b0c8b-ffffffff821b0ca6: do_sched_rt_period_timer.cold (STB_LOCAL)
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
In kernel/sched/rt.c (ffff80001014fbc8)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (c039d928)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (c0000000001a3ad4)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffe0000f83c2)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e88e0)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810d82c5)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e5435)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810f14c6)
Location: kernel/sched/rt.c:812
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
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
