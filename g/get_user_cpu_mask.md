# Function: <code>get_user_cpu_mask</code>

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
In kernel/sched/core.c (ffffffff810adfd9)
Location: kernel/sched/core.c:4488
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810b09f7)
Location: kernel/sched/core.c:4738
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810b6be9)
Location: kernel/sched/core.c:4775
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2e37)
Location: kernel/sched/core.c:4672
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba237)
Location: kernel/sched/core.c:4716
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc850)
Location: kernel/sched/core.c:4851
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810bc850-ffffffff810bc8bc: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c36d0)
Location: kernel/sched/core.c:4836
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810c36d0-ffffffff810c373c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb6a0)
Location: kernel/sched/core.c:5289
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810cb6a0-ffffffff810cb70c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d38d0)
Location: kernel/sched/core.c:5480
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810d38d0-ffffffff810d393c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddc80)
Location: kernel/sched/core.c:5713
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810ddc80-ffffffff810ddcf4: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da260)
Location: kernel/sched/core.c:6537
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810da260-ffffffff810da2cd: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc350)
Location: kernel/sched/core.c:6838
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810dc350-ffffffff810dc3ba: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ef190)
Location: kernel/sched/core.c:8031
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810ef190-ffffffff810ef1fa: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110ab40)
Location: kernel/sched/core.c:8139
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8110ab40-ffffffff8110abb1: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81132130)
Location: kernel/sched/core.c:8323
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff81132130-ffffffff811321a1: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811403a0)
Location: kernel/sched/core.c:8432
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff811403a0-ffffffff81140411: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114b450)
Location: kernel/sched/core.c:8443
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8114b450-ffffffff8114b4c1: get_user_cpu_mask (STB_LOCAL)
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
In kernel/sched/core.c (ffff80001013c788)
Location: kernel/sched/core.c:5480
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setaffinity
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
In kernel/sched/core.c (c038cb28)
Location: kernel/sched/core.c:5480
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
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
In kernel/sched/core.c (c00000000018ae6c)
Location: kernel/sched/core.c:5480
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffe0000ebf3c)
Location: kernel/sched/core.c:5480
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
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
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cdbc0)
Location: kernel/sched/core.c:5480
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810cdbc0-ffffffff810cdc2c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc450)
Location: kernel/sched/core.c:5480
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810bc450-ffffffff810bc4bc: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd030)
Location: kernel/sched/core.c:5480
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810cd030-ffffffff810cd09c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_user_cpu_mask(long unsigned int *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d59c0)
Location: kernel/sched/core.c:5480
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff810d59c0-ffffffff810d5a2c: get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
