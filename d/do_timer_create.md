# Function: <code>do_timer_create</code>

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
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107e80)
Location: kernel/time/posix-timers.c:493
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
```
**Symbols:**

```
ffffffff81107e80-ffffffff811082f4: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81113030)
Location: kernel/time/posix-timers.c:499
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
```
**Symbols:**

```
ffffffff81113030-ffffffff811134a3: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111f780)
Location: kernel/time/posix-timers.c:508
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8111f780-ffffffff8111fbeb: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112af50)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8112af50-ffffffff8112b3cb: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81135fd0)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff81135fd0-ffffffff8113646b: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81142070)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff81142070-ffffffff8114250b: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811509d0)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff811509d0-ffffffff81150de9: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cc50)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8114cc50-ffffffff8114d06e: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f050)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8114f050-ffffffff8114f56e: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81173200)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff81173200-ffffffff81173748: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a6520)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff811a6520-ffffffff811a6a68: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e60c0)
Location: kernel/time/posix-timers.c:498
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff811e60c0-ffffffff811e6608: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fa700)
Location: kernel/time/posix-timers.c:444
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff811fa700-ffffffff811fac08: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff812108f0)
Location: kernel/time/posix-timers.c:444
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff812108f0-ffffffff81210df8: do_timer_create (STB_LOCAL)
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
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ac180)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__arm64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__arm64_sys_timer_create
  - kernel/time/posix-timers.c:__arm64_sys_timer_create
```
**Symbols:**

```
ffff8000101ac180-ffff8000101ac784: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f6528)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_create
```
**Symbols:**

```
c03f6528-c03f6a00: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020fd70)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_compat_sys_timer_create
  - kernel/time/posix-timers.c:__se_compat_sys_timer_create
  - kernel/time/posix-timers.c:__se_sys_timer_create
  - kernel/time/posix-timers.c:__se_sys_timer_create
```
**Symbols:**

```
c00000000020fd70-c0000000002103b4: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe0001360da)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_create
  - kernel/time/posix-timers.c:__se_sys_timer_create
```
**Symbols:**

```
ffffffe0001360da-ffffffe0001364bc: do_timer_create (STB_LOCAL)
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
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113a820)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8113a820-ffffffff8113acbb: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112d270)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff8112d270-ffffffff8112d705: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138540)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff81138540-ffffffff811389db: do_timer_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_timer_create(clockid_t which_clock, struct sigevent *event, timer_t *created_timer_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811450f0)
Location: kernel/time/posix-timers.c:472
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
  - kernel/time/posix-timers.c:__x64_sys_timer_create
```
**Symbols:**

```
ffffffff811450f0-ffffffff811455a7: do_timer_create (STB_LOCAL)
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
