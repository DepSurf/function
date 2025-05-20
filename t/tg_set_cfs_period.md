# Function: <code>tg_set_cfs_period</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaba5)
Location: kernel/sched/core.c:8393
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810b0c70-ffffffff810b0c8e: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad7e5)
Location: kernel/sched/core.c:8452
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810b3760-ffffffff810b377e: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b38e5)
Location: kernel/sched/core.c:8605
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810b9da0-ffffffff810b9dbe: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af875)
Location: kernel/sched/core.c:6458
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810b45f0-ffffffff810b460e: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6b35)
Location: kernel/sched/core.c:6526
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810bb8c0-ffffffff810bb8de: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc725)
Location: kernel/sched/core.c:6646
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810c2d60-ffffffff810c2d7e: tg_set_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_period(struct task_group *tg, long int cfs_period_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4f05)
Location: kernel/sched/core.c:6627
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810cc050-ffffffff810cc06e: tg_set_cfs_period (STB_GLOBAL)
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
In kernel/sched/core.c (ffffffff810ce565)
Location: kernel/sched/core.c:7106
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810d8165)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810df4f5)
Location: kernel/sched/core.c:7734
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810dc1d5)
Location: kernel/sched/core.c:8699
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810de1f5)
Location: kernel/sched/core.c:9075
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810f2f35)
Location: kernel/sched/core.c:10320
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff8110ed15)
Location: kernel/sched/core.c:10643
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff81135af5)
Location: kernel/sched/core.c:10789
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff81144c95)
Location: kernel/sched/core.c:10949
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff811501b5)
Location: kernel/sched/core.c:10906
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffff80001013893c)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (c0387648)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (c0000000001846d0)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffe0000e8810)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810d2635)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810c0c65)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810d03e5)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
In kernel/sched/core.c (ffffffff810d9d75)
Location: kernel/sched/core.c:7490
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
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
</ul>
