# Function: <code>__copy_siginfo_from_user32</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa1e0)
Location: kernel/signal.c:3273
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810aa1e0-ffffffff810aa25e: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af270)
Location: kernel/signal.c:3402
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810af270-ffffffff810af2ec: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5890)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b5890-ffffffff810b590c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bbc40)
Location: kernel/signal.c:3425
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810bbc40-ffffffff810bbcbc: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6f00)
Location: kernel/signal.c:3445
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b6f00-ffffffff810b6f7c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8500)
Location: kernel/signal.c:3467
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b8500-ffffffff810b857c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca9f0)
Location: kernel/signal.c:3555
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810ca9f0-ffffffff810caa6c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2340)
Location: kernel/signal.c:3537
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810e2340-ffffffff810e23d8: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811026f0)
Location: kernel/signal.c:3539
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff811026f0-ffffffff81102788: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110e930)
Location: kernel/signal.c:3563
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8110e930-ffffffff8110e9c8: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811182b0)
Location: kernel/signal.c:3574
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff811182b0-ffffffff81118348: __copy_siginfo_from_user32 (STB_LOCAL)
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101119d8)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffff8000101119d8-ffff800010111bb0: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159680)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
c000000000159680-c000000000159730: __copy_siginfo_from_user32 (STB_LOCAL)
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afc00)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810afc00-ffffffff810afc7c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e520)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109e520-ffffffff8109e59c: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af160)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810af160-ffffffff810af1dc: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7430)
Location: kernel/signal.c:3407
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b7430-ffffffff810b74ac: __copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
