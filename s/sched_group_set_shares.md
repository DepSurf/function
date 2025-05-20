# Function: <code>sched_group_set_shares</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bec80)
Location: kernel/sched/fair.c:8219
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810bec80-ffffffff810bed90: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2570)
Location: kernel/sched/fair.c:8710
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c2684: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c85f0)
Location: kernel/sched/fair.c:9331
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c85f0-ffffffff810c8706: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c22c0)
Location: kernel/sched/fair.c:9356
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c22c0-ffffffff810c2915: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9970)
Location: kernel/sched/fair.c:9825
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c9970-ffffffff810ca109: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1ad0)
Location: kernel/sched/fair.c:10332
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810d1ad0-ffffffff810d20c7: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db410)
Location: kernel/sched/fair.c:10436
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810db410-ffffffff810dba56: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e28a0)
Location: kernel/sched/fair.c:10376
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810e28a0-ffffffff810e29cb: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecf50)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810ecf50-ffffffff810ed07b: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6e60)
Location: kernel/sched/fair.c:11056
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810f6e60-ffffffff810f6f8b: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5040)
Location: kernel/sched/fair.c:11170
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810f5040-ffffffff810f51a5: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f7130)
Location: kernel/sched/fair.c:11236
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810f7130-ffffffff810f728f: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811114d0)
Location: kernel/sched/fair.c:11638
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff811114d0-ffffffff81111526: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112d6f0)
Location: kernel/sched/fair.c:11756
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8112d6f0-ffffffff8112d747: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811574c0)
Location: kernel/sched/fair.c:12272
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff811574c0-ffffffff81157517: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81167510)
Location: kernel/sched/fair.c:12590
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81167510-ffffffff81167567: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81174300)
Location: kernel/sched/fair.c:13013
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81174300-ffffffff81174357: sched_group_set_shares (STB_GLOBAL)
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
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014d558)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffff80001014d558-ffff80001014d710: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039b150)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c039b150-c039b284: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001a0450)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c0000000001a0450-c0000000001a0628: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f684c)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffe0000f684c-ffffffe0000f69b4: sched_group_set_shares (STB_GLOBAL)
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
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e70b0)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810e70b0-ffffffff810e71db: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6250)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810d6250-ffffffff810d637b: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3480)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810e3480-ffffffff810e35ab: sched_group_set_shares (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef060)
Location: kernel/sched/fair.c:10371
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_shares_write_u64
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810ef060-ffffffff810ef18b: sched_group_set_shares (STB_GLOBAL)
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
