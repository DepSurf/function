# Function: <code>__cgroup_account_cputime_field</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/stat.c (ffffffff81135650)
Location: kernel/cgroup/stat.c:235
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81135650-ffffffff8113568b: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81144080)
Location: kernel/cgroup/rstat.c:371
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81144080-ffffffff811440b9: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114fb90)
Location: kernel/cgroup/rstat.c:371
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8114fb90-ffffffff8114fbc9: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115ba90)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8115ba90-ffffffff8115bacc: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811676b0)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff811676b0-ffffffff811676ec: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178f10)
Location: kernel/cgroup/rstat.c:368
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81178f10-ffffffff81178f4c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175c20)
Location: kernel/cgroup/rstat.c:367
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81175c20-ffffffff81175c5c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811767a0)
Location: kernel/cgroup/rstat.c:378
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff811767a0-ffffffff811767dc: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119e020)
Location: kernel/cgroup/rstat.c:378
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8119e020-ffffffff8119e05c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811ce360)
Location: kernel/cgroup/rstat.c:383
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff811ce360-ffffffff811ce3cb: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81211b30)
Location: kernel/cgroup/rstat.c:419
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff81211b30-ffffffff81211ba3: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81227490)
Location: kernel/cgroup/rstat.c:403
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff81227490-ffffffff81227503: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123f2a0)
Location: kernel/cgroup/rstat.c:450
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__account_forceidle_time
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
**Symbols:**

```
ffffffff8123f2a0-ffffffff8123f313: __cgroup_account_cputime_field (STB_GLOBAL)
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
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d9d20)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffff8000101d9d20-ffff8000101d9dac: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041c67c)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
c041c67c-c041c71c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c000000000246f40)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
c000000000246f40-c000000000246fc4: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe000152628)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffe000152628-ffffffe00015269c: __cgroup_account_cputime_field (STB_GLOBAL)
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
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115fcd0)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8115fcd0-ffffffff8115fd0c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152f50)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff81152f50-ffffffff81152f8c: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115daa0)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8115daa0-ffffffff8115dadc: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cgroup_account_cputime_field(struct cgroup *cgrp, enum cpu_usage_stat index, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116acf0)
Location: kernel/cgroup/rstat.c:374
Inline: False
Direct callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_user_time
```
**Symbols:**

```
ffffffff8116acf0-ffffffff8116ad31: __cgroup_account_cputime_field (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
