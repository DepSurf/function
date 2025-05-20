# Function: <code>__getparam_dl</code>

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
In kernel/sched/core.c (ffffffff810adda5)
Location: kernel/sched/core.c:3702
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
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
In kernel/sched/core.c (ffffffff810b0774)
Location: kernel/sched/core.c:3955
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
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
In kernel/sched/core.c (ffffffff810b6904)
Location: kernel/sched/core.c:3992
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c9010)
Location: kernel/sched/deadline.c:2514
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
**Symbols:**

```
ffffffff810c9010-ffffffff810c904f: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0700)
Location: kernel/sched/deadline.c:2501
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
**Symbols:**

```
ffffffff810d0700-ffffffff810d073f: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8c30)
Location: kernel/sched/deadline.c:2586
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810d8c30-ffffffff810d8c6c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e2730)
Location: kernel/sched/deadline.c:2589
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810e2730-ffffffff810e276c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9240)
Location: kernel/sched/deadline.c:2580
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810e9240-ffffffff810e927c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4d20)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810f4d20-ffffffff810f4d5c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe430)
Location: kernel/sched/deadline.c:2626
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810fe430-ffffffff810fe46c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fcc30)
Location: kernel/sched/deadline.c:2753
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810fcc30-ffffffff810fcc6c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fefb0)
Location: kernel/sched/deadline.c:2737
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810fefb0-ffffffff810fefec: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff8111ae70)
Location: kernel/sched/deadline.c:2750
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff8111ae70-ffffffff8111aebd: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8113adf0)
Location: kernel/sched/deadline.c:2900
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff8113adf0-ffffffff8113ae49: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811656e0)
Location: kernel/sched/deadline.c:2900
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff811656e0-ffffffff81165739: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175ea0)
Location: kernel/sched/deadline.c:2926
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
```
**Symbols:**

```
ffffffff81175ea0-ffffffff81175ef9: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81184100)
Location: kernel/sched/deadline.c:3023
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff81184100-ffffffff81184159: __getparam_dl (STB_GLOBAL)
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
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010157440)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_getattr
```
**Symbols:**

```
ffff800010157440-ffff800010157490: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a51d8)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
```
**Symbols:**

```
c03a51d8-c03a5224: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001abff0)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
```
**Symbols:**

```
c0000000001abff0-c0000000001ac024: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fe298)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
```
**Symbols:**

```
ffffffe0000fe298-ffffffe0000fe2dc: __getparam_dl (STB_GLOBAL)
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
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ee120)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810ee120-ffffffff810ee15c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de1b0)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810de1b0-ffffffff810de1ec: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb250)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810eb250-ffffffff810eb28c: __getparam_dl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __getparam_dl(struct task_struct *p, struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f6250)
Location: kernel/sched/deadline.c:2627
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
```
**Symbols:**

```
ffffffff810f6250-ffffffff810f628c: __getparam_dl (STB_GLOBAL)
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
