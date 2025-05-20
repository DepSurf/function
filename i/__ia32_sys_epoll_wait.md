# Function: <code>__ia32_sys_epoll_wait</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ea960)
Location: fs/eventpoll.c:2197
Inline: False
```
**Symbols:**

```
ffffffff812ea960-ffffffff812ea981: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81300b80)
Location: fs/eventpoll.c:2223
Inline: False
```
**Symbols:**

```
ffffffff81300b80-ffffffff81300ba1: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81321e20)
Location: fs/eventpoll.c:2301
Inline: False
```
**Symbols:**

```
ffffffff81321e20-ffffffff81321e41: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cbe00)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff81334380-ffffffff813343a1: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8136e930)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff8136e930-ffffffff8136e951: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8137bce0)
Location: kernel/sys_ni.c:407
Inline: False
```
**Symbols:**

```
ffffffff8137bce0-ffffffff8137bdd2: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81382440)
Location: kernel/sys_ni.c:413
Inline: False
```
**Symbols:**

```
ffffffff81382440-ffffffff81382535: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813cf6b0)
Location: kernel/sys_ni.c:411
Inline: False
```
**Symbols:**

```
ffffffff813cf6b0-ffffffff813cf7a5: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81459280)
Location: kernel/sys_ni.c:414
Inline: False
```
**Symbols:**

```
ffffffff81459280-ffffffff8145938d: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814e86a0)
Location: kernel/sys_ni.c:414
Inline: False
```
**Symbols:**

```
ffffffff814e86a0-ffffffff814e87ad: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8151edc0)
Location: kernel/sys_ni.c:307
Inline: False
```
**Symbols:**

```
ffffffff8151edc0-ffffffff8151eecd: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff815533d0)
Location: kernel/sys_ni.c:326
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff815533d0-ffffffff815534dd: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c6180)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff8132c960-ffffffff8132c981: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b49a0)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff8131c230-ffffffff8131c251: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c56d0)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff8132a430-ffffffff8132a451: __ia32_sys_epoll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_sys_epoll_wait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cdb10)
Location: kernel/sys_ni.c:406
Inline: False
```
**Symbols:**

```
ffffffff8133af00-ffffffff8133af21: __ia32_sys_epoll_wait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs *regs</code>
</li>
</ul>
</details>
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
