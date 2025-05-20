# Function: <code>tg_get_cfs_period</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4d35)
Location: kernel/sched/core.c:8403
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_period_read_u64
  - kernel/sched/core.c:tg_cfs_schedulable_down
```
**Symbols:**

```
ffffffff810b0c90-ffffffff810b0cbd: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a8392)
Location: kernel/sched/core.c:8462
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810b3780-ffffffff810b37ad: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae272)
Location: kernel/sched/core.c:8615
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810b9dc0-ffffffff810b9ded: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aac9e)
Location: kernel/sched/core.c:6468
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810b4610-ffffffff810b463d: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6b82)
Location: kernel/sched/core.c:6536
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810bb8e0-ffffffff810bb90d: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc790)
Location: kernel/sched/core.c:6656
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810c2d80-ffffffff810c2dad: tg_get_cfs_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_period(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4f70)
Location: kernel/sched/core.c:6637
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
```
**Symbols:**

```
ffffffff810cc070-ffffffff810cc09d: tg_get_cfs_period (STB_GLOBAL)
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
In kernel/sched/core.c (ffffffff810ce63a)
Location: kernel/sched/core.c:7119
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810d823a)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810df5ca)
Location: kernel/sched/core.c:7747
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810dc2aa)
Location: kernel/sched/core.c:8712
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810de2ca)
Location: kernel/sched/core.c:9088
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810f301c)
Location: kernel/sched/core.c:10334
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff8110ee36)
Location: kernel/sched/core.c:10657
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff81135c36)
Location: kernel/sched/core.c:10803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff81144dd6)
Location: kernel/sched/core.c:10963
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff811502f6)
Location: kernel/sched/core.c:10920
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffff800010138a38)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (c0387714)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (c0000000001847b8)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffe0000e88c0)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810d270a)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810c0d3a)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810d04ba)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
In kernel/sched/core.c (ffffffff810d9e4a)
Location: kernel/sched/core.c:7503
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
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
