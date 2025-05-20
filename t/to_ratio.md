# Function: <code>to_ratio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4c06)
Location: kernel/sched/core.c:2266
Inline: True
Inline callers:
  - kernel/sched/core.c:__setscheduler_params
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
Direct callers:
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810accb0-ffffffff810accd9: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a83cf)
Location: kernel/sched/core.c:2445
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
Direct callers:
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810af6f0-ffffffff810af719: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae2af)
Location: kernel/sched/core.c:2455
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
Direct callers:
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810b5830-ffffffff810b5859: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aace2)
Location: kernel/sched/core.c:2406
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810b1a90-ffffffff810b1abb: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b19fb)
Location: kernel/sched/core.c:2425
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810b8e60-ffffffff810b8e8b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8aab)
Location: kernel/sched/core.c:2401
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810c0940-ffffffff810c096b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1bc8)
Location: kernel/sched/core.c:2390
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810c9cb0-ffffffff810c9cdb: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8fe8)
Location: kernel/sched/core.c:2801
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810d1950-ffffffff810d197b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d20b8)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810db910-ffffffff810db93b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbfe8)
Location: kernel/sched/core.c:3081
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810e47d0-ffffffff810e47fb: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d87f8)
Location: kernel/sched/core.c:3796
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810e22e0-ffffffff810e230b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da15b)
Location: kernel/sched/core.c:3817
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810e40f0-ffffffff810e411b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810eda9b)
Location: kernel/sched/core.c:4429
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810fae00-ffffffff810fae2b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110879b)
Location: kernel/sched/core.c:4607
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
```
**Symbols:**

```
ffffffff81117210-ffffffff8111724f: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112d74b)
Location: kernel/sched/core.c:4746
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
```
**Symbols:**

```
ffffffff8113e710-ffffffff8113e74f: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ab8b)
Location: kernel/sched/core.c:4824
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
```
**Symbols:**

```
ffffffff8114b220-ffffffff8114b25f: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81145a0f)
Location: kernel/sched/core.c:4845
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:__setparam_dl
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:init_dl_rq_bw_ratio
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_dl_bw
```
**Symbols:**

```
ffffffff81156e50-ffffffff81156e8f: to_ratio (STB_GLOBAL)
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
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010132608)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffff80001013b628-ffff80001013b678: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038370c)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
c038aef0-c038af54: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d22c)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
c000000000189410-c000000000189448: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e5512)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffe0000eaac4-ffffffe0000eab0c: to_ratio (STB_GLOBAL)
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
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc438)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810d5da0-ffffffff810d5dcb: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b99f8)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810c4410-ffffffff810c443b: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb958)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810d2bb0-ffffffff810d2bdb: to_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int to_ratio(u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3eb8)
Location: kernel/sched/core.c:2921
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_cfs_schedulable_down
Direct callers:
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:__setparam_dl
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:init_dl_rq_bw_ratio
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:init_dl_bw
```
**Symbols:**

```
ffffffff810dd690-ffffffff810dd6bb: to_ratio (STB_GLOBAL)
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
