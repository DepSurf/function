# Function: <code>swake_up_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c7560)
Location: kernel/sched/swait.c:19
Inline: False
Direct callers:
  - kernel/sched/swait.c:swake_up
```
**Symbols:**

```
ffffffff810c7560-ffffffff810c759d: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810cd430)
Location: kernel/sched/swait.c:19
Inline: False
Direct callers:
  - kernel/sched/swait.c:swake_up
```
**Symbols:**

```
ffffffff810cd430-ffffffff810cd46d: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810c9ee6)
Location: kernel/sched/swait.c:19
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up
Direct callers:
  - kernel/sched/swait.c:swake_up
```
**Symbols:**

```
ffffffff810c9e70-ffffffff810c9e9f: swake_up_locked.part.2 (STB_LOCAL)
ffffffff810c9ea0-ffffffff810c9ebf: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d1704)
Location: kernel/sched/swait.c:20
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up
Direct callers:
  - kernel/sched/swait.c:swake_up
```
**Symbols:**

```
ffffffff810d16a0-ffffffff810d16cf: swake_up_locked.part.2 (STB_LOCAL)
ffffffff810d16d0-ffffffff810d16ef: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810d9ccb)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up
Direct callers:
  - kernel/sched/swait.c:swake_up
```
**Symbols:**

```
ffffffff810d9c60-ffffffff810d9c8f: swake_up_locked.part.5 (STB_LOCAL)
ffffffff810d9c90-ffffffff810d9cae: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810e385b)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810e37f0-ffffffff810e381f: swake_up_locked.part.6 (STB_LOCAL)
ffffffff810e3820-ffffffff810e383e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ea47d)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810ea410-ffffffff810ea43f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810ea440-ffffffff810ea45e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f5e4d)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810f5de0-ffffffff810f5e0f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810f5e10-ffffffff810f5e2e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ff5de)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/swait.c:swake_up_all_locked
Direct callers:
  - kernel/sched/completion.c:complete
```
**Symbols:**

```
ffffffff810ff710-ffffffff810ff750: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff810fdfee)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/swait.c:swake_up_all_locked
Direct callers:
  - kernel/sched/completion.c:complete
```
**Symbols:**

```
ffffffff810fe220-ffffffff810fe260: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff811003ce)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/swait.c:swake_up_all_locked
Direct callers:
  - kernel/sched/completion.c:complete
```
**Symbols:**

```
ffffffff81100510-ffffffff81100550: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/swait.c (ffffffff8111c44e)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/swait.c:swake_up_all_locked
Direct callers:
  - kernel/sched/completion.c:complete
```
**Symbols:**

```
ffffffff8111c570-ffffffff8111c5b0: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141ebd)
Location: kernel/sched/swait.c:21
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete
```
**Symbols:**

```
ffffffff81141e40-ffffffff81141e94: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116cf3d)
Location: kernel/sched/swait.c:21
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete
```
**Symbols:**

```
ffffffff8116cc90-ffffffff8116cce4: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d85d)
Location: kernel/sched/swait.c:21
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete
```
**Symbols:**

```
ffffffff8117d3b0-ffffffff8117d404: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q, int wake_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118baad)
Location: kernel/sched/swait.c:21
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete_on_current_cpu
  - kernel/sched/build_utility.c:complete_on_current_cpu
```
**Symbols:**

```
ffffffff8118b770-ffffffff8118b7d3: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffff800010159660)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffff8000101592a0-ffff8000101592e4: swake_up_locked.part.0 (STB_LOCAL)
ffff8000101592e8-ffff800010159324: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (c03a6a08)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
c03a6978-c03a69b0: swake_up_locked.part.0 (STB_LOCAL)
c03a69b0-c03a69dc: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (c0000000001adac4)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
c0000000001ada00-c0000000001ada5c: swake_up_locked.part.0 (STB_LOCAL)
c0000000001ada60-c0000000001ada84: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffe0000ff52a)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffe0000ff49a-ffffffe0000ff4d4: swake_up_locked.part.0 (STB_LOCAL)
ffffffe0000ff4d4-ffffffe0000ff508: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ef24d)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810ef1e0-ffffffff810ef20f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810ef210-ffffffff810ef22e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810df2cd)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810df260-ffffffff810df28f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810df290-ffffffff810df2ae: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810ec37d)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810ec310-ffffffff810ec33f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810ec340-ffffffff810ec35e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swake_up_locked(struct swait_queue_head *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/swait.c (ffffffff810f74ad)
Location: kernel/sched/swait.c:22
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_one
Direct callers:
  - kernel/sched/swait.c:swake_up_one
```
**Symbols:**

```
ffffffff810f7440-ffffffff810f746f: swake_up_locked.part.0 (STB_LOCAL)
ffffffff810f7470-ffffffff810f748e: swake_up_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int wake_flags</code>
</li>
</ul>
</details>
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
