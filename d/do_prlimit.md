# Function: <code>do_prlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810954f0)
Location: kernel/sys.c:1375
Inline: False
Direct callers:
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_setrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_getrlimit
```
**Symbols:**

```
ffffffff810954f0-ffffffff810956f2: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81098890)
Location: kernel/sys.c:1375
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getrlimit
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
```
**Symbols:**

```
ffffffff81098890-ffffffff81098a95: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109d840)
Location: kernel/sys.c:1375
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_getrlimit
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
```
**Symbols:**

```
ffffffff8109d840-ffffffff8109da44: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109a7b0)
Location: kernel/sys.c:1480
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:compat_SyS_getrlimit
  - kernel/sys.c:compat_SyS_setrlimit
  - kernel/sys.c:SyS_getrlimit
```
**Symbols:**

```
ffffffff8109a7b0-ffffffff8109aa46: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1490)
Location: kernel/sys.c:1487
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:compat_SyS_getrlimit
  - kernel/sys.c:compat_SyS_setrlimit
  - kernel/sys.c:SyS_getrlimit
```
**Symbols:**

```
ffffffff810a1490-ffffffff810a1726: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a7500)
Location: kernel/sys.c:1541
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810a7500-ffffffff810a7706: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b0210)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810b0210-ffffffff810b0416: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5be0)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810b5be0-ffffffff810b5df3: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bc1d0)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810bc1d0-ffffffff810bc3b6: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c3b70)
Location: kernel/sys.c:1558
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810c3b70-ffffffff810c3d56: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bef60)
Location: kernel/sys.c:1559
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810bef60-ffffffff810bf146: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c08f0)
Location: kernel/sys.c:1576
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810c08f0-ffffffff810c0ad2: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d33e0)
Location: kernel/sys.c:1585
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__x64_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x64_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810d33e0-ffffffff810d35c2: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810eb572)
Location: kernel/sys.c:1449
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_compat_sys_setrlimit
```
**Symbols:**

```
ffffffff810e8dd0-ffffffff810e8fe1: do_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110c752)
Location: kernel/sys.c:1452
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_compat_sys_setrlimit
```
**Symbols:**

```
ffffffff81109650-ffffffff81109883: do_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81118912)
Location: kernel/sys.c:1470
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_compat_sys_setrlimit
```
**Symbols:**

```
ffffffff811159e0-ffffffff81115c13: do_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81122302)
Location: kernel/sys.c:1470
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_compat_sys_setrlimit
```
**Symbols:**

```
ffffffff8111f3d0-ffffffff8111f603: do_prlimit (STB_LOCAL)
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
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010118ca8)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_sys_getrlimit
```
**Symbols:**

```
ffff800010118ca8-ffff800010118ee4: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036d724)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
```
**Symbols:**

```
c036d724-c036d904: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001607a0)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_compat_sys_getrlimit
  - kernel/sys.c:__se_compat_sys_setrlimit
  - kernel/sys.c:__se_sys_getrlimit
```
**Symbols:**

```
c0000000001607a0-c000000000160a50: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d41f2)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
```
**Symbols:**

```
ffffffe0000d41f2-ffffffe0000d43a4: do_prlimit (STB_GLOBAL)
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
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6540)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810b6540-ffffffff810b6726: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4e80)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810a4e80-ffffffff810a5066: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5aa0)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810b5aa0-ffffffff810b5c86: do_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_prlimit(struct task_struct *tsk, unsigned int resource, struct rlimit *new_rlim, struct rlimit *old_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bde10)
Location: kernel/sys.c:1542
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
**Symbols:**

```
ffffffff810bde10-ffffffff810bdfe6: do_prlimit (STB_GLOBAL)
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
