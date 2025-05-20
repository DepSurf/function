# Function: <code>nohz_run_idle_balance</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6a40)
Location: kernel/sched/fair.c:10570
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810f6a40-ffffffff810f6aa5: nohz_run_idle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811109b0)
Location: kernel/sched/fair.c:10812
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff811109b0-ffffffff81110a66: nohz_run_idle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112cb80)
Location: kernel/sched/fair.c:10928
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff8112cb80-ffffffff8112cc59: nohz_run_idle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81156880)
Location: kernel/sched/fair.c:11455
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff81156880-ffffffff81156959: nohz_run_idle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81166900)
Location: kernel/sched/fair.c:11759
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff81166900-ffffffff811669c7: nohz_run_idle_balance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nohz_run_idle_balance(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81173640)
Location: kernel/sched/fair.c:12234
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff81173640-ffffffff81173707: nohz_run_idle_balance (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
