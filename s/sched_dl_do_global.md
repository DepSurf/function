# Function: <code>sched_dl_do_global</code>

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
In kernel/sched/core.c (ffffffff810b0a82)
Location: kernel/sched/core.c:8085
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
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
In kernel/sched/core.c (ffffffff810b3579)
Location: kernel/sched/core.c:8121
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
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
In kernel/sched/core.c (ffffffff810b9bc6)
Location: kernel/sched/core.c:8274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c8bc0)
Location: kernel/sched/deadline.c:2405
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810c8bc0-ffffffff810c8cb3: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d02e0)
Location: kernel/sched/deadline.c:2392
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810d02e0-ffffffff810d03ca: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8800)
Location: kernel/sched/deadline.c:2474
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810d8800-ffffffff810d88ea: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e2300)
Location: kernel/sched/deadline.c:2477
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810e2300-ffffffff810e23ea: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8e00)
Location: kernel/sched/deadline.c:2468
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810e8e00-ffffffff810e8ee9: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f48e0)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810f48e0-ffffffff810f49c9: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fdff0)
Location: kernel/sched/deadline.c:2514
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fdff0-ffffffff810fe0d9: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc660)
Location: kernel/sched/deadline.c:2634
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fc660-ffffffff810fc785: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe9b0)
Location: kernel/sched/deadline.c:2618
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fe9b0-ffffffff810fead5: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111a370)
Location: kernel/sched/deadline.c:2631
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff8111a370-ffffffff8111a4f5: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8113a100)
Location: kernel/sched/deadline.c:2784
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff8113a100-ffffffff8113a2a1: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81164990)
Location: kernel/sched/deadline.c:2784
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81164990-ffffffff81164b33: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175130)
Location: kernel/sched/deadline.c:2810
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81175130-ffffffff811752d3: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81183440)
Location: kernel/sched/deadline.c:2907
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81183440-ffffffff811835e4: sched_dl_do_global (STB_GLOBAL)
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
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010156ef8)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffff800010156ef8-ffff800010157088: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a4af4)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
c03a4af4-c03a4c10: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001ab9d0)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
c0000000001ab9d0-c0000000001abb34: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fde30)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffe0000fde30-ffffffe0000fdf38: sched_dl_do_global (STB_GLOBAL)
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
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810edce0)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810edce0-ffffffff810eddc9: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ddd70)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810ddd70-ffffffff810dde59: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eae10)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810eae10-ffffffff810eaef9: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_dl_do_global();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5de0)
Location: kernel/sched/deadline.c:2515
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810f5de0-ffffffff810f5ee5: sched_dl_do_global (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
