# Function: <code>sched_dl_overflow</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c8cc0)
Location: kernel/sched/deadline.c:2442
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810c8cc0-ffffffff810c8f9d: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d03d0)
Location: kernel/sched/deadline.c:2429
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d03d0-ffffffff810d068b: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d88f0)
Location: kernel/sched/deadline.c:2511
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d88f0-ffffffff810d8bb5: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e23f0)
Location: kernel/sched/deadline.c:2514
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e23f0-ffffffff810e26b5: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8ef0)
Location: kernel/sched/deadline.c:2505
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e8ef0-ffffffff810e91ce: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f49d0)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f49d0-ffffffff810f4cae: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe0e0)
Location: kernel/sched/deadline.c:2551
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fe0e0-ffffffff810fe3b1: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc790)
Location: kernel/sched/deadline.c:2675
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fc790-ffffffff810fcbb5: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810feae0)
Location: kernel/sched/deadline.c:2659
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810feae0-ffffffff810fef36: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:2672
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81ca6f2f-ffffffff81ca6fa7: sched_dl_overflow.cold (STB_LOCAL)
ffffffff8111a500-ffffffff8111aded: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:2822
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81e56899-ffffffff81e56910: sched_dl_overflow.cold (STB_LOCAL)
ffffffff8113a4a0-ffffffff8113ad6e: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:2822
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff82057ab9-ffffffff82057b30: sched_dl_overflow.cold (STB_LOCAL)
ffffffff81164d60-ffffffff8116563f: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:2848
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff820d62df-ffffffff820d6356: sched_dl_overflow.cold (STB_LOCAL)
ffffffff81175500-ffffffff81175df8: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:2945
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff821b14a7-ffffffff821b151e: sched_dl_overflow.cold (STB_LOCAL)
ffffffff81183800-ffffffff81184054: sched_dl_overflow (STB_GLOBAL)
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
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010157088)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffff800010157088-ffff8000101573d8: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a4c10)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c03a4c10-c03a5158: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001abb40)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c0000000001abb40-c0000000001abf58: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fdf38)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffe0000fdf38-ffffffe0000fe22c: sched_dl_overflow (STB_GLOBAL)
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
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eddd0)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810eddd0-ffffffff810ee0ae: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dde60)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810dde60-ffffffff810de13e: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eaf00)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810eaf00-ffffffff810eb1de: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_dl_overflow(struct task_struct *p, int policy, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5ef0)
Location: kernel/sched/deadline.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f5ef0-ffffffff810f61d3: sched_dl_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
