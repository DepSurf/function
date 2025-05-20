# Function: <code>__set_cpus_allowed_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab500)
Location: kernel/sched/core.c:1205
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff810ab500-ffffffff810ab717: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae1a0)
Location: kernel/sched/core.c:1123
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810ae1a0-ffffffff810ae37a: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4300)
Location: kernel/sched/core.c:1134
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810b4300-ffffffff810b44db: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b02d0)
Location: kernel/sched/core.c:1059
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810b02d0-ffffffff810b04d7: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7700)
Location: kernel/sched/core.c:1074
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810b7700-ffffffff810b7907: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf290)
Location: kernel/sched/core.c:1071
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810bf290-ffffffff810bf473: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8590)
Location: kernel/sched/core.c:1066
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810c8590-ffffffff810c8773: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:1509
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810cff90-ffffffff810d018e: __set_cpus_allowed_ptr (STB_LOCAL)
ffffffff810d4595-ffffffff810d45a8: __set_cpus_allowed_ptr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9f10)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810d9f10-ffffffff810da133: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2bd0)
Location: kernel/sched/core.c:1694
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810e2bd0-ffffffff810e2dd6: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0330)
Location: kernel/sched/core.c:2326
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:migrate_enable
```
**Symbols:**

```
ffffffff810e0330-ffffffff810e04a5: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2150)
Location: kernel/sched/core.c:2347
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:migrate_enable
```
**Symbols:**

```
ffffffff810e2150-ffffffff810e22c5: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fc3d8)
Location: kernel/sched/core.c:2841
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff81ca5d8b-ffffffff81ca5df4: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811189df)
Location: kernel/sched/core.c:2940
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
**Symbols:**

```
ffffffff81e556c8-ffffffff81e55751: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113bb90)
Location: kernel/sched/core.c:2998
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
```
**Symbols:**

```
ffffffff8113bb90-ffffffff8113bc4b: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114f0b0)
Location: kernel/sched/core.c:3174
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
```
**Symbols:**

```
ffffffff8114f0b0-ffffffff8114f16b: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115af50)
Location: kernel/sched/core.c:3204
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
```
**Symbols:**

```
ffffffff8115af50-ffffffff8115b00b: __set_cpus_allowed_ptr (STB_LOCAL)
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
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101398e8)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffff8000101398e8-ffff800010139b44: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03896c4)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
c03896c4-c038991c: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000186d40)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
c000000000186d40-c00000000018705c: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e94da)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffe0000e94da-ffffffe0000e9728: __set_cpus_allowed_ptr (STB_LOCAL)
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
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d43c0)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810d43c0-ffffffff810d45e3: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2a10)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810c2a10-ffffffff810c2c33: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1200)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810d1200-ffffffff810d1423: __set_cpus_allowed_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask, bool check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbb70)
Location: kernel/sched/core.c:1629
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_setaffinity
```
**Symbols:**

```
ffffffff810dbb70-ffffffff810dbd8f: __set_cpus_allowed_ptr (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool check</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *new_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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
