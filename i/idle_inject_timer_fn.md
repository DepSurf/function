# Function: <code>idle_inject_timer_fn</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd7f0)
Location: kernel/sched/idle.c:280
Inline: False
```
**Symbols:**

```
ffffffff810cd7f0-ffffffff810cd811: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca210)
Location: kernel/sched/idle.c:286
Inline: False
```
**Symbols:**

```
ffffffff810ca210-ffffffff810ca231: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d19f0)
Location: kernel/sched/idle.c:286
Inline: False
```
**Symbols:**

```
ffffffff810d19f0-ffffffff810d1a11: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c40b0)
Location: kernel/sched/idle.c:303
Inline: False
```
**Symbols:**

```
ffffffff810c40b0-ffffffff810c40d1: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd3b0)
Location: kernel/sched/idle.c:303
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81883ca0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffffffff810cd3b0-ffffffff810cd3d1: idle_inject_timer_fn (STB_LOCAL)
ffffffff81883ca0-ffffffff81883ce8: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d5770)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce3b0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffffffff810d5770-ffffffff810d5791: idle_inject_timer_fn (STB_LOCAL)
ffffffff818ce3b0-ffffffff818ce3f8: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810dfd80)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff819007a0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffffffff810dfd80-ffffffff810dfda1: idle_inject_timer_fn (STB_LOCAL)
ffffffff819007a0-ffffffff819007e8: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e8080)
Location: kernel/sched/idle.c:321
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff819d7770)
Location: drivers/powercap/idle_inject.c:107
Inline: False
```
**Symbols:**

```
ffffffff810e8080-ffffffff810e80a1: idle_inject_timer_fn (STB_LOCAL)
ffffffff819d7770-ffffffff819d780e: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5ca0)
Location: kernel/sched/idle.c:345
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff819d68b0)
Location: drivers/powercap/idle_inject.c:108
Inline: False
```
**Symbols:**

```
ffffffff810e5ca0-ffffffff810e5cc1: idle_inject_timer_fn (STB_LOCAL)
ffffffff819d68b0-ffffffff819d694e: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7c60)
Location: kernel/sched/idle.c:351
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff819bca30)
Location: drivers/powercap/idle_inject.c:108
Inline: False
```
**Symbols:**

```
ffffffff810e7c60-ffffffff810e7c81: idle_inject_timer_fn (STB_LOCAL)
ffffffff819bca30-ffffffff819bcace: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff340)
Location: kernel/sched/idle.c:351
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81a6bee0)
Location: drivers/powercap/idle_inject.c:108
Inline: False
```
**Symbols:**

```
ffffffff810ff340-ffffffff810ff361: idle_inject_timer_fn (STB_LOCAL)
ffffffff81a6bee0-ffffffff81a6bfab: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112ecc0)
Location: kernel/sched/idle.c:348
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81bdc990)
Location: drivers/powercap/idle_inject.c:108
Inline: False
```
**Symbols:**

```
ffffffff8112ecc0-ffffffff8112ece7: idle_inject_timer_fn (STB_LOCAL)
ffffffff81bdc990-ffffffff81bdca62: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81158a90)
Location: kernel/sched/idle.c:348
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87bb0)
Location: drivers/powercap/idle_inject.c:108
Inline: False
```
**Symbols:**

```
ffffffff81158a90-ffffffff81158ab7: idle_inject_timer_fn (STB_LOCAL)
ffffffff81d87bb0-ffffffff81d87c04: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81168c60)
Location: kernel/sched/idle.c:327
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81df6190)
Location: drivers/powercap/idle_inject.c:124
Inline: False
```
**Symbols:**

```
ffffffff81168c60-ffffffff81168c87: idle_inject_timer_fn (STB_LOCAL)
ffffffff81df6190-ffffffff81df61fd: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175f10)
Location: kernel/sched/idle.c:357
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81eac880)
Location: drivers/powercap/idle_inject.c:124
Inline: False
```
**Symbols:**

```
ffffffff81175f10-ffffffff81175f37: idle_inject_timer_fn (STB_LOCAL)
ffffffff81eac880-ffffffff81eac8ed: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013f970)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffff800010b8ffc0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffff80001013f970-ffff80001013f9c8: idle_inject_timer_fn (STB_LOCAL)
ffff800010b8ffc0-ffff800010b9001c: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c038f87c)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (c0c7a02c)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
c038f87c-c038f8bc: idle_inject_timer_fn (STB_LOCAL)
c0c7a02c-c0c7a090: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018e7f0)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (c000000000c6f1a0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
c00000000018e7f0-c00000000018e824: idle_inject_timer_fn (STB_LOCAL)
c000000000c6f1a0-c000000000c6f224: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000edbec)
Location: kernel/sched/idle.c:304
Inline: False
```
**Symbols:**

```
ffffffe0000edbec-ffffffe0000edc18: idle_inject_timer_fn (STB_LOCAL)
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d9f70)
Location: kernel/sched/idle.c:304
Inline: False
```
**Symbols:**

```
ffffffff810d9f70-ffffffff810d9f91: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c8fa0)
Location: kernel/sched/idle.c:304
Inline: False
```
**Symbols:**

```
ffffffff810c8fa0-ffffffff810c8fc1: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d62b0)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff818f11c0)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffffffff810d62b0-ffffffff810d62d1: idle_inject_timer_fn (STB_LOCAL)
ffffffff818f11c0-ffffffff818f1208: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer *timer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1bf0)
Location: kernel/sched/idle.c:304
Inline: False
```
```
In drivers/powercap/idle_inject.c (ffffffff81912240)
Location: drivers/powercap/idle_inject.c:105
Inline: False
```
**Symbols:**

```
ffffffff810e1bf0-ffffffff810e1c11: idle_inject_timer_fn (STB_LOCAL)
ffffffff81912240-ffffffff81912288: idle_inject_timer_fn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
