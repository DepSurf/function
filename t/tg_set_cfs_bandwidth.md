# Function: <code>tg_set_cfs_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa8f0)
Location: kernel/sched/core.c:8294
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
```
**Symbols:**

```
ffffffff810aa8f0-ffffffff810aab64: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad530)
Location: kernel/sched/core.c:8353
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810ad530-ffffffff810ad7a1: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3630)
Location: kernel/sched/core.c:8506
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b3630-ffffffff810b38a3: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af570)
Location: kernel/sched/core.c:6356
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810af570-ffffffff810af831: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6850)
Location: kernel/sched/core.c:6424
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810b6850-ffffffff810b6aff: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc490)
Location: kernel/sched/core.c:6544
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810bc490-ffffffff810bc6e7: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4c70)
Location: kernel/sched/core.c:6525
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810c4c70-ffffffff810c4ec7: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce310)
Location: kernel/sched/core.c:7002
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810ce310-ffffffff810ce55b: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7f10)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810d7f10-ffffffff810d815b: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df200)
Location: kernel/sched/core.c:7624
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810df200-ffffffff810df4ea: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbea0)
Location: kernel/sched/core.c:8589
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810dbea0-ffffffff810dc1c3: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddec0)
Location: kernel/sched/core.c:8965
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810ddec0-ffffffff810de1e3: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota, u64 burst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:10203
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_burst_write_u64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810f2b50-ffffffff810f2eeb: tg_set_cfs_bandwidth (STB_LOCAL)
ffffffff81ca5c8e-ffffffff81ca5ca9: tg_set_cfs_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota, u64 burst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:10526
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_burst_write_u64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff8110e920-ffffffff8110eca1: tg_set_cfs_bandwidth (STB_LOCAL)
ffffffff81e555aa-ffffffff81e555c5: tg_set_cfs_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota, u64 burst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:10672
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_burst_write_u64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff811356e0-ffffffff81135a67: tg_set_cfs_bandwidth (STB_LOCAL)
ffffffff820569f3-ffffffff82056a0e: tg_set_cfs_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota, u64 burst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:10832
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_burst_write_u64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff81144840-ffffffff81144c04: tg_set_cfs_bandwidth (STB_LOCAL)
ffffffff820d50df-ffffffff820d50fa: tg_set_cfs_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota, u64 burst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:10789
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_burst_write_u64
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff8114fd80-ffffffff81150121: tg_set_cfs_bandwidth (STB_LOCAL)
ffffffff821b0002-ffffffff821b001d: tg_set_cfs_bandwidth.cold (STB_LOCAL)
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
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138610)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffff800010138610-ffff800010138920: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03872b8)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
c03872b8-c0387630: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001842d0)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
c0000000001842d0-c0000000001846bc: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8580)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffe0000e8580-ffffffe0000e87f6: tg_set_cfs_bandwidth (STB_LOCAL)
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
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d23e0)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810d23e0-ffffffff810d262b: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0a20)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810c0a20-ffffffff810c0c5f: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0190)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810d0190-ffffffff810d03db: tg_set_cfs_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tg_set_cfs_bandwidth(struct task_group *tg, u64 period, u64 quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9b00)
Location: kernel/sched/core.c:7386
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_cfs_period_write_u64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
  - kernel/sched/core.c:cpu_cfs_quota_write_s64
```
**Symbols:**

```
ffffffff810d9b00-ffffffff810d9d66: tg_set_cfs_bandwidth (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 burst</code>
</li>
</ul>
</details>
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
