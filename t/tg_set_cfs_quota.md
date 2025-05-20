# Function: <code>tg_set_cfs_quota</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aab76)
Location: kernel/sched/core.c:8367
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b0c10-ffffffff810b0c3d: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad7b6)
Location: kernel/sched/core.c:8426
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b3700-ffffffff810b372d: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b38b6)
Location: kernel/sched/core.c:8579
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b9d40-ffffffff810b9d6d: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af846)
Location: kernel/sched/core.c:6432
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b4590-ffffffff810b45bd: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6b06)
Location: kernel/sched/core.c:6500
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810bb860-ffffffff810bb88d: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc6f5)
Location: kernel/sched/core.c:6620
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810c2d00-ffffffff810c2d2d: tg_set_cfs_quota (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tg_set_cfs_quota(struct task_group *tg, long int cfs_quota_us);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4ed5)
Location: kernel/sched/core.c:6601
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810cbff0-ffffffff810cc01d: tg_set_cfs_quota (STB_GLOBAL)
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
In kernel/sched/core.c (ffffffff810ce5a5)
Location: kernel/sched/core.c:7078
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810d81a5)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810df535)
Location: kernel/sched/core.c:7706
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810dc215)
Location: kernel/sched/core.c:8671
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810de235)
Location: kernel/sched/core.c:9047
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810f2f75)
Location: kernel/sched/core.c:10291
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff8110ed75)
Location: kernel/sched/core.c:10614
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff81135b65)
Location: kernel/sched/core.c:10760
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff81144d05)
Location: kernel/sched/core.c:10920
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff81150225)
Location: kernel/sched/core.c:10877
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffff8000101389a4)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (c0387690)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (c000000000184720)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffe0000e885c)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810d2675)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810c0ca5)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810d0425)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
In kernel/sched/core.c (ffffffff810d9db5)
Location: kernel/sched/core.c:7462
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
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
