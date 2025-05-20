# Function: <code>tick_nohz_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff810fe5f0)
Location: kernel/time/tick-sched.c:557
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810fe5f0-ffffffff810fe65b: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81105980)
Location: kernel/time/tick-sched.c:649
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff81105980-ffffffff811059eb: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8110ce30)
Location: kernel/time/tick-sched.c:647
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff8110ce30-ffffffff8110ce9b: tick_nohz_restart (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8110f589)
Location: kernel/time/tick-sched.c:657
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
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
In kernel/time/tick-sched.c (ffffffff8111a869)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
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
In kernel/time/tick-sched.c (ffffffff8112703f)
Location: kernel/time/tick-sched.c:623
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff8113272f)
Location: kernel/time/tick-sched.c:620
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff8113d2aa)
Location: kernel/time/tick-sched.c:629
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff81148e3d)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811588b0)
Location: kernel/time/tick-sched.c:658
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811588b0-ffffffff8115892b: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811548c0)
Location: kernel/time/tick-sched.c:706
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811548c0-ffffffff81154939: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81155d40)
Location: kernel/time/tick-sched.c:707
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff81155d40-ffffffff81155db9: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8117a9d0)
Location: kernel/time/tick-sched.c:742
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff8117a9d0-ffffffff8117aa49: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811b0260)
Location: kernel/time/tick-sched.c:758
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811b0260-ffffffff811b02f5: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811f0d10)
Location: kernel/time/tick-sched.c:758
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811f0d10-ffffffff811f0da5: tick_nohz_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81205730)
Location: kernel/time/tick-sched.c:774
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff81205730-ffffffff812057d5: tick_nohz_restart (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff8121bc12)
Location: kernel/time/tick-sched.c:775
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
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
In kernel/time/tick-sched.c (ffff8000101b4df8)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (c03fed4c)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (c00000000021a904)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffe00013b4f2)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff8114145d)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff811342dd)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
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
In kernel/time/tick-sched.c (ffffffff8113f30d)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff8114bd6d)
Location: kernel/time/tick-sched.c:633
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
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
</ul>
