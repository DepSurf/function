# Function: <code>__copy_siginfo_from_user</code>

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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4c90)
Location: kernel/signal.c:3087
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a4c90-ffffffff810a4cec: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9630)
Location: kernel/signal.c:3216
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a9630-ffffffff810a968c: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afed0)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810afed0-ffffffff810aff2c: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7a50)
Location: kernel/signal.c:3239
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b7a50-ffffffff810b7b0f: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2ce0)
Location: kernel/signal.c:3259
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b2ce0-ffffffff810b2d9f: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4310)
Location: kernel/signal.c:3287
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b4310-ffffffff810b43cf: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c64c0)
Location: kernel/signal.c:3375
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810c64c0-ffffffff810c659a: __copy_siginfo_from_user (STB_LOCAL)
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
In kernel/signal.c (ffffffff810e2d20)
Location: kernel/signal.c:3355
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff811031e0)
Location: kernel/signal.c:3357
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8110f420)
Location: kernel/signal.c:3381
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff81118da0)
Location: kernel/signal.c:3392
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c638)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__arm64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffff80001010c638-ffff80001010c738: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03647f8)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
**Symbols:**

```
c03647f8-c03648c4: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001526e0)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
**Symbols:**

```
c0000000001526e0-c000000000152798: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd5ec)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffe0000cd5ec-ffffffe0000cd650: __copy_siginfo_from_user (STB_LOCAL)
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa240)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810aa240-ffffffff810aa29c: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098940)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81098940-ffffffff8109899c: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a97a0)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a97a0-ffffffff810a97fc: __copy_siginfo_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1b30)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b1b30-ffffffff810b1b8c: __copy_siginfo_from_user (STB_LOCAL)
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
