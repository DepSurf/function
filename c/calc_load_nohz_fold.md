# Function: <code>calc_load_nohz_fold</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b4870)
Location: kernel/sched/loadavg.c:220
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
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
In kernel/sched/loadavg.c (ffffffff810bbb40)
Location: kernel/sched/loadavg.c:221
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
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
In kernel/sched/loadavg.c (ffffffff810c3210)
Location: kernel/sched/loadavg.c:217
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
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
In kernel/sched/loadavg.c (ffffffff810cc4c0)
Location: kernel/sched/loadavg.c:271
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
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
In kernel/sched/loadavg.c (ffffffff810d4900)
Location: kernel/sched/loadavg.c:271
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810decc0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffff810decc0-ffffffff810ded1a: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e7195)
Location: kernel/sched/loadavg.c:234
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e4dd5)
Location: kernel/sched/loadavg.c:234
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
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
In kernel/sched/loadavg.c (ffffffff810e6ca5)
Location: kernel/sched/loadavg.c:234
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
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
In kernel/sched/loadavg.c (ffffffff810fe275)
Location: kernel/sched/loadavg.c:234
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
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
In kernel/sched/build_utility.c (ffffffff811487b5)
Location: kernel/sched/loadavg.c:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
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
In kernel/sched/build_utility.c (ffffffff81176fb5)
Location: kernel/sched/loadavg.c:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187c05)
Location: kernel/sched/loadavg.c:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
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
In kernel/sched/build_utility.c (ffffffff811963b5)
Location: kernel/sched/loadavg.c:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
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
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffff80001013e6f8)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffff80001013e6f8-ffff80001013e790: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c038e6e4)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
c038e6e4-c038e770: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c00000000018d8a0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
c00000000018d8a0-c00000000018d924: calc_load_nohz_fold (STB_LOCAL)
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
In kernel/sched/loadavg.c (ffffffe0000ed1b0)
Location: kernel/sched/loadavg.c:234
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
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
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d8eb0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffff810d8eb0-ffffffff810d8f0a: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c78b0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffff810c78b0-ffffffff810c790a: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d51f0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffff810d51f0-ffffffff810d524a: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void calc_load_nohz_fold(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e0aa0)
Location: kernel/sched/loadavg.c:234
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffff810e0aa0-ffffffff810e0afa: calc_load_nohz_fold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
