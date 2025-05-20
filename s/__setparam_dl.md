# Function: <code>__setparam_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4bdc)
Location: kernel/sched/core.c:3616
Inline: True
Inline callers:
  - kernel/sched/core.c:__setscheduler_params
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac66a)
Location: kernel/sched/core.c:3869
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2788)
Location: kernel/sched/core.c:3906
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c8fa0)
Location: kernel/sched/deadline.c:2502
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810c8fa0-ffffffff810c900b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0690)
Location: kernel/sched/deadline.c:2489
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d0690-ffffffff810d06fb: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8bc0)
Location: kernel/sched/deadline.c:2574
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810d8bc0-ffffffff810d8c2b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e26c0)
Location: kernel/sched/deadline.c:2577
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e26c0-ffffffff810e272b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e91d0)
Location: kernel/sched/deadline.c:2568
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810e91d0-ffffffff810e923b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4cb0)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f4cb0-ffffffff810f4d1b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe3c0)
Location: kernel/sched/deadline.c:2614
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fe3c0-ffffffff810fe42e: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fcbc0)
Location: kernel/sched/deadline.c:2741
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fcbc0-ffffffff810fcc2e: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fef40)
Location: kernel/sched/deadline.c:2725
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810fef40-ffffffff810fefae: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111adf0)
Location: kernel/sched/deadline.c:2738
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff8111adf0-ffffffff8111ae63: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8113ad70)
Location: kernel/sched/deadline.c:2888
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff8113ad70-ffffffff8113adef: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81165650)
Location: kernel/sched/deadline.c:2888
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81165650-ffffffff811656cf: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175e10)
Location: kernel/sched/deadline.c:2914
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81175e10-ffffffff81175e8f: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81184070)
Location: kernel/sched/deadline.c:3011
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff81184070-ffffffff811840ef: __setparam_dl (STB_GLOBAL)
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
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101573d8)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffff8000101573d8-ffff800010157440: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a5158)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c03a5158-c03a51d8: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001abf60)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c0000000001abf60-c0000000001abfec: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fe22c)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffe0000fe22c-ffffffe0000fe298: __setparam_dl (STB_GLOBAL)
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
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ee0b0)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810ee0b0-ffffffff810ee11b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de140)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810de140-ffffffff810de1ab: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb1e0)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810eb1e0-ffffffff810eb24b: __setparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __setparam_dl(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f61e0)
Location: kernel/sched/deadline.c:2615
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffff810f61e0-ffffffff810f624b: __setparam_dl (STB_GLOBAL)
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
