# Function: <code>__sched_clock_gtod_offset</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810cc880)
Location: kernel/sched/clock.c:198
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810cc880-ffffffff810cc8ba: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4c90)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810d4c90-ffffffff810d4cca: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df250)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810df250-ffffffff810df28a: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7761)
Location: kernel/sched/clock.c:199
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810e7530-ffffffff810e756d: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e53a1)
Location: kernel/sched/clock.c:199
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810e5170-ffffffff810e51ad: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7351)
Location: kernel/sched/clock.c:199
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810e7120-ffffffff810e715d: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe96e)
Location: kernel/sched/clock.c:199
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
Direct callers:
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810fe720-ffffffff810fe75d: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114540d)
Location: kernel/sched/clock.c:197
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
Direct callers:
  - kernel/sched/build_utility.c:sched_clock_init
```
**Symbols:**

```
ffffffff81e57340-ffffffff81e57380: __sched_clock_gtod_offset (STB_LOCAL)
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
In kernel/sched/build_utility.c (ffffffff8117252d)
Location: kernel/sched/clock.c:197
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
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
In kernel/sched/build_utility.c (ffffffff8118358d)
Location: kernel/sched/clock.c:197
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
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
In kernel/sched/build_utility.c (ffffffff81191ccd)
Location: kernel/sched/clock.c:197
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d9440)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810d9440-ffffffff810d947a: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c7e20)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810c7e20-ffffffff810c7e5a: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d5780)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810d5780-ffffffff810d57ba: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sched_clock_gtod_offset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e1050)
Location: kernel/sched/clock.c:199
Inline: False
Direct callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:sched_clock_init
```
**Symbols:**

```
ffffffff810e1050-ffffffff810e108a: __sched_clock_gtod_offset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
