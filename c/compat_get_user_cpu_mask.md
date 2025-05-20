# Function: <code>compat_get_user_cpu_mask</code>

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
In kernel/compat.c (ffffffff811117e8)
Location: kernel/compat.c:602
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
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
In kernel/compat.c (ffffffff81118f38)
Location: kernel/compat.c:602
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
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
In kernel/compat.c (ffffffff8112067a)
Location: kernel/compat.c:610
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
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
In kernel/compat.c (ffffffff81120f74)
Location: kernel/compat.c:331
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
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
In kernel/compat.c (ffffffff8112c5e4)
Location: kernel/compat.c:308
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113ad90)
Location: kernel/compat.c:265
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8113ad90-ffffffff8113ade2: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81146610)
Location: kernel/compat.c:265
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff81146610-ffffffff81146662: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151760)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff81151760-ffffffff811517ac: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d3b0)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8115d3b0-ffffffff8115d3fc: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116ddf0)
Location: kernel/compat.c:110
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8116ddf0-ffffffff8116de35: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a3f0)
Location: kernel/compat.c:110
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8116a3f0-ffffffff8116a435: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116b060)
Location: kernel/compat.c:110
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff8116b060-ffffffff8116b0a5: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190c60)
Location: kernel/compat.c:110
Inline: False
Direct callers:
  - kernel/compat.c:__x64_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff81190c60-ffffffff81190ca5: compat_get_user_cpu_mask (STB_LOCAL)
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
In kernel/compat.c (ffffffff811c0537)
Location: kernel/compat.c:110
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
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
In kernel/compat.c (ffffffff8120291c)
Location: kernel/compat.c:110
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
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
In kernel/compat.c (ffffffff81217cdc)
Location: kernel/compat.c:110
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
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
In kernel/compat.c (ffffffff8122f89c)
Location: kernel/compat.c:110
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
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
In kernel/compat.c (ffff8000101cd810)
Location: kernel/compat.c:198
Inline: True
Inline callers:
  - kernel/compat.c:__arm64_compat_sys_sched_setaffinity
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000237308)
Location: kernel/compat.c:198
Inline: True
Inline callers:
  - kernel/compat.c:__do_compat_sys_sched_setaffinity
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811559d0)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff811559d0-ffffffff81155a1c: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148cf0)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff81148cf0-ffffffff81148d3c: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811537a0)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff811537a0-ffffffff811537ec: compat_get_user_cpu_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_get_user_cpu_mask(compat_ulong_t *user_mask_ptr, unsigned int len, struct cpumask *new_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811606a0)
Location: kernel/compat.c:198
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff811606a0-ffffffff811606ec: compat_get_user_cpu_mask (STB_LOCAL)
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
