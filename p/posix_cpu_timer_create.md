# Function: <code>posix_cpu_timer_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f27a0)
Location: kernel/time/posix-cpu-timers.c:342
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff810f27a0-ffffffff810f2860: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f98b0)
Location: kernel/time/posix-cpu-timers.c:341
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff810f98b0-ffffffff810f9970: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107240)
Location: kernel/time/posix-cpu-timers.c:340
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81107240-ffffffff81107300: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109600)
Location: kernel/time/posix-cpu-timers.c:321
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81109600-ffffffff811096d5: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811147d0)
Location: kernel/time/posix-cpu-timers.c:322
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811147d0-ffffffff811148a5: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81120f70)
Location: kernel/time/posix-cpu-timers.c:323
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff81120f70-ffffffff81121047: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112c690)
Location: kernel/time/posix-cpu-timers.c:323
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff8112c690-ffffffff8112c767: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137020)
Location: kernel/time/posix-cpu-timers.c:323
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff81137020-ffffffff81137113: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811432cb)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff81143210-ffffffff81143254: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152890)
Location: kernel/time/posix-cpu-timers.c:378
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81152890-ffffffff8115290c: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114eae0)
Location: kernel/time/posix-cpu-timers.c:378
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff8114eae0-ffffffff8114eb66: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114ff70)
Location: kernel/time/posix-cpu-timers.c:378
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff8114ff70-ffffffff8114fff6: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81174160)
Location: kernel/time/posix-cpu-timers.c:380
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81174160-ffffffff811741e6: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a8e90)
Location: kernel/time/posix-cpu-timers.c:387
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811a8e90-ffffffff811a8f27: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e8d00)
Location: kernel/time/posix-cpu-timers.c:387
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811e8d00-ffffffff811e8d97: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fd7d0)
Location: kernel/time/posix-cpu-timers.c:386
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811fd7d0-ffffffff811fd867: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812139d0)
Location: kernel/time/posix-cpu-timers.c:386
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff812139d0-ffffffff81213a67: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad3dc)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffff8000101ad2f0-ffff8000101ad350: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f8360)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
c03f8290-c03f82e0: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c0000000002116c8)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
c000000000211590-c000000000211604: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe0001373d6)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffe000137328-ffffffe000137370: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113ba7b)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff8113b9c0-ffffffff8113ba04: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e43b)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff8112e380-ffffffff8112e3c4: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113979b)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff811396e0-ffffffff81139724: posix_cpu_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_timer_create(struct k_itimer *new_timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114626b)
Location: kernel/time/posix-cpu-timers.c:387
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
**Symbols:**

```
ffffffff811461b0-ffffffff811461f4: posix_cpu_timer_create (STB_LOCAL)
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
