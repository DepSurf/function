# Function: <code>tg_get_cfs_quota</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4d05)
Location: kernel/sched/core.c:8380
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
  - kernel/sched/core.c:tg_cfs_schedulable_down
```
**Symbols:**

```
ffffffff810b0c40-ffffffff810b0c70: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a83ad)
Location: kernel/sched/core.c:8439
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810b3730-ffffffff810b3760: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae28d)
Location: kernel/sched/core.c:8592
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810b9d70-ffffffff810b9da0: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aacb9)
Location: kernel/sched/core.c:6445
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810b45c0-ffffffff810b45f0: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3798)
Location: kernel/sched/core.c:6513
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810bb890-ffffffff810bb8c0: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba998)
Location: kernel/sched/core.c:6633
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810c2d30-ffffffff810c2d60: tg_get_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3bb8)
Location: kernel/sched/core.c:6614
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
ffffffff810cc020-ffffffff810cc050: tg_get_cfs_quota (STB_GLOBAL)
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
In kernel/sched/core.c (ffffffff810c9cb7)
Location: kernel/sched/core.c:7093
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810d2d57)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810dc999)
Location: kernel/sched/core.c:7721
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810d9209)
Location: kernel/sched/core.c:8686
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810dab99)
Location: kernel/sched/core.c:9062
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810ee769)
Location: kernel/sched/core.c:10307
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff8110adb8)
Location: kernel/sched/core.c:10630
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff8112fbd8)
Location: kernel/sched/core.c:10776
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff8113d648)
Location: kernel/sched/core.c:10936
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff811487a8)
Location: kernel/sched/core.c:10893
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffff800010133024)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int tg_get_cfs_quota(struct task_group *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03833f0)
Location: kernel/sched/core.c:7477
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
```
**Symbols:**

```
c03833f0-c0383470: tg_get_cfs_quota (STB_LOCAL)
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
In kernel/sched/core.c (c00000000017de50)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffe0000e5d52)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810cd0d7)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810bb8d7)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810cc6c7)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
In kernel/sched/core.c (ffffffff810d4ea7)
Location: kernel/sched/core.c:7477
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_quota_read_s64
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
<b>Arch</b>
<ul>
</ul>
