# Function: <code>watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c01e7)
Location: kernel/sched/rt.c:2187
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff8113a400)
Location: kernel/hung_task.c:225
Inline: False
```
```
In kernel/watchdog.c (ffffffff8113a920)
Location: kernel/watchdog.c:542
Inline: False
```
**Symbols:**

```
ffffffff8113a400-ffffffff8113a70e: watchdog (STB_LOCAL)
ffffffff8113a920-ffffffff8113a960: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3c17)
Location: kernel/sched/rt.c:2250
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff81142910)
Location: kernel/hung_task.c:227
Inline: False
```
```
In kernel/watchdog.c (ffffffff81142e50)
Location: kernel/watchdog.c:558
Inline: False
```
**Symbols:**

```
ffffffff81142910-ffffffff81142c36: watchdog (STB_LOCAL)
ffffffff81142e50-ffffffff81142e90: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9c87)
Location: kernel/sched/rt.c:2248
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff8114c6f0)
Location: kernel/hung_task.c:228
Inline: False
```
```
In kernel/watchdog.c (ffffffff8114d210)
Location: kernel/watchdog.c:426
Inline: False
```
**Symbols:**

```
ffffffff8114c6f0-ffffffff8114ca41: watchdog (STB_LOCAL)
ffffffff8114d210-ffffffff8114d250: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4997)
Location: kernel/sched/rt.c:2341
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff8114e660)
Location: kernel/hung_task.c:237
Inline: False
```
```
In kernel/watchdog.c (ffffffff8114ef80)
Location: kernel/watchdog.c:497
Inline: False
```
**Symbols:**

```
ffffffff8114e660-ffffffff8114e9ca: watchdog (STB_LOCAL)
ffffffff8114ef80-ffffffff8114efc0: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cc047)
Location: kernel/sched/rt.c:2268
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff8115aef0)
Location: kernel/hung_task.c:237
Inline: False
```
```
In kernel/watchdog.c (ffffffff8115b2f0)
Location: kernel/watchdog.c:513
Inline: False
```
**Symbols:**

```
ffffffff8115aef0-ffffffff8115b25d: watchdog (STB_LOCAL)
ffffffff8115b2f0-ffffffff8115b31c: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d36d7)
Location: kernel/sched/rt.c:2279
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:240
Inline: False
```
```
In kernel/watchdog.c (ffffffff81169f00)
Location: kernel/watchdog.c:513
Inline: False
```
**Symbols:**

```
ffffffff81169b30-ffffffff81169df2: watchdog (STB_LOCAL)
ffffffff81169e32-ffffffff81169eae: watchdog.cold.2 (STB_LOCAL)
ffffffff81169f00-ffffffff81169f2c: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dca8b)
Location: kernel/sched/rt.c:2290
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:269
Inline: False
```
**Symbols:**

```
ffffffff811769c0-ffffffff81176cee: watchdog (STB_LOCAL)
ffffffff81176d22-ffffffff81176da3: watchdog.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e3a33)
Location: kernel/sched/rt.c:2290
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff811837a0-ffffffff81183b2e: watchdog (STB_LOCAL)
ffffffff81183b62-ffffffff81183c06: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ef573)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff8118f610-ffffffff8118f99e: watchdog (STB_LOCAL)
ffffffff8118f9d2-ffffffff8118fa76: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8e71)
Location: kernel/sched/rt.c:2352
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff811a44a0)
Location: kernel/hung_task.c:277
Inline: False
```
**Symbols:**

```
ffffffff811a44a0-ffffffff811a4542: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7061)
Location: kernel/sched/rt.c:2392
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff811a15f0)
Location: kernel/hung_task.c:276
Inline: False
```
**Symbols:**

```
ffffffff811a15f0-ffffffff811a1692: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f91b1)
Location: kernel/sched/rt.c:2399
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffff811a2250)
Location: kernel/hung_task.c:276
Inline: False
```
**Symbols:**

```
ffffffff811a2250-ffffffff811a22f1: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff81114782)
Location: kernel/sched/rt.c:2424
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:277
Inline: False
```
**Symbols:**

```
ffffffff811cba30-ffffffff811cbadf: watchdog (STB_LOCAL)
ffffffff81cb3e9c-ffffffff81cb3eb0: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81137f65)
Location: kernel/sched/rt.c:2601
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:351
Inline: False
```
**Symbols:**

```
ffffffff811ff7f0-ffffffff811ff89f: watchdog (STB_LOCAL)
ffffffff81e64d49-ffffffff81e64d5d: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81162625)
Location: kernel/sched/rt.c:2600
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:359
Inline: False
```
**Symbols:**

```
ffffffff81247210-ffffffff812472bf: watchdog (STB_LOCAL)
ffffffff8205c913-ffffffff8205c927: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81172da5)
Location: kernel/sched/rt.c:2604
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:361
Inline: False
```
**Symbols:**

```
ffffffff8125e2a0-ffffffff8125e34f: watchdog (STB_LOCAL)
ffffffff820db289-ffffffff820db29d: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811806b5)
Location: kernel/sched/rt.c:2553
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:361
Inline: False
```
**Symbols:**

```
ffffffff812781e0-ffffffff8127828f: watchdog (STB_LOCAL)
ffffffff821b6fb0-ffffffff821b6fc4: watchdog.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff8000101507d4)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffff800010206d08)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffff800010206d08-ffff8000102070cc: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039e498)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (c0445a88)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
c0445a88-c0445ef8: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a4898)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (c0000000002831b0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
c0000000002831b0-c0000000002836bc: watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f8eaa)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (ffffffe000169566)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffe000169566-ffffffe0001698f6: watchdog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e8df3)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff81187c30-ffffffff81187fbe: watchdog (STB_LOCAL)
ffffffff81187ff2-ffffffff81188096: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d8933)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff8117ad70-ffffffff8117b0fe: watchdog (STB_LOCAL)
ffffffff8117b132-ffffffff8117b1d6: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e5aa3)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff81185a00-ffffffff81185d8e: watchdog (STB_LOCAL)
ffffffff81185dc2-ffffffff81185e66: watchdog.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void watchdog(struct rq *rq, struct task_struct *p);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0983)
Location: kernel/sched/rt.c:2280
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/hung_task.c (0)
Location: kernel/hung_task.c:271
Inline: False
```
**Symbols:**

```
ffffffff81193350-ffffffff811936df: watchdog (STB_LOCAL)
ffffffff81193712-ffffffff811937b4: watchdog.cold (STB_LOCAL)
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
