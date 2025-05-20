# Function: <code>sched_dl_global_validate</code>

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
In kernel/sched/core.c (ffffffff810b0946)
Location: kernel/sched/core.c:8049
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
In kernel/sched/core.c (ffffffff810b3436)
Location: kernel/sched/core.c:8085
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
In kernel/sched/core.c (ffffffff810b9a86)
Location: kernel/sched/core.c:8238
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
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c8a20)
Location: kernel/sched/deadline.c:2356
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810c8a20-ffffffff810c8ae1: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0140)
Location: kernel/sched/deadline.c:2343
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810d0140-ffffffff810d01fd: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8660)
Location: kernel/sched/deadline.c:2425
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810d8660-ffffffff810d871d: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e2160)
Location: kernel/sched/deadline.c:2428
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810e2160-ffffffff810e221d: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8c50)
Location: kernel/sched/deadline.c:2419
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810e8c50-ffffffff810e8d14: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4730)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810f4730-ffffffff810f47f4: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fdf20)
Location: kernel/sched/deadline.c:2465
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fdf20-ffffffff810fdfe4: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc4f0)
Location: kernel/sched/deadline.c:2582
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fc4f0-ffffffff810fc659: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe830)
Location: kernel/sched/deadline.c:2566
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810fe830-ffffffff810fe9ac: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111a180)
Location: kernel/sched/deadline.c:2579
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff8111a180-ffffffff8111a363: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139ec0)
Location: kernel/sched/deadline.c:2732
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81139ec0-ffffffff8113a0f4: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81164750)
Location: kernel/sched/deadline.c:2732
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81164750-ffffffff81164980: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174ef0)
Location: kernel/sched/deadline.c:2758
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff81174ef0-ffffffff81175120: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811831f0)
Location: kernel/sched/deadline.c:2855
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_rt_handler
```
**Symbols:**

```
ffffffff811831f0-ffffffff81183421: sched_dl_global_validate (STB_GLOBAL)
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
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010156cb0)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffff800010156cb0-ffff800010156e18: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a48fc)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
c03a48fc-c03a49f8: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001ab720)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
c0000000001ab720-c0000000001ab8a8: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fdc38)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffe0000fdc38-ffffffe0000fdd40: sched_dl_global_validate (STB_GLOBAL)
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
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810edb30)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810edb30-ffffffff810edbf4: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ddbc0)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810ddbc0-ffffffff810ddc84: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eac60)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810eac60-ffffffff810ead24: sched_dl_global_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_dl_global_validate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5c10)
Location: kernel/sched/deadline.c:2466
Inline: False
Direct callers:
  - kernel/sched/rt.c:sched_rt_handler
```
**Symbols:**

```
ffffffff810f5c10-ffffffff810f5cf5: sched_dl_global_validate (STB_GLOBAL)
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
