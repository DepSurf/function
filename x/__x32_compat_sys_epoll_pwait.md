# Function: <code>__x32_compat_sys_epoll_pwait</code>

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
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812eb380)
Location: fs/eventpoll.c:2248
Inline: False
```
**Symbols:**

```
ffffffff812eb380-ffffffff812eb492: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81300cf0)
Location: fs/eventpoll.c:2256
Inline: False
```
**Symbols:**

```
ffffffff81300cf0-ffffffff81300d8d: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff81322ab3-ffffffff81322ac5: __x32_compat_sys_epoll_pwait.cold (STB_LOCAL)
ffffffff81321fb0-ffffffff81322070: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81334510)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff81334510-ffffffff813345c3: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8136eac0)
Location: kernel/sys_ni.c:70
Inline: False
```
**Symbols:**

```
ffffffff8136eac0-ffffffff8136eb73: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8137bf30)
Location: kernel/sys_ni.c:70
Inline: False
```
**Symbols:**

```
ffffffff8137bf30-ffffffff8137c059: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81382690)
Location: kernel/sys_ni.c:70
Inline: False
```
**Symbols:**

```
ffffffff81382690-ffffffff813827b9: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132caf0)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff8132caf0-ffffffff8132cba3: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131ca10)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff8131ca10-ffffffff8131cac3: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132a5c0)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff8132a5c0-ffffffff8132a673: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_epoll_pwait(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133cbf0)
Location: fs/eventpoll.c:2332
Inline: False
```
**Symbols:**

```
ffffffff8133cbf0-ffffffff8133cca3: __x32_compat_sys_epoll_pwait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
