# Function: <code>sigset_from_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sigset_from_compat(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110f770)
Location: kernel/compat.c:974
Inline: True
Inline callers:
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigaction
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
```
**Symbols:**

```
ffffffff8110f770-ffffffff8110f781: sigset_from_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sigset_from_compat(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811177c2)
Location: kernel/compat.c:974
Inline: True
Inline callers:
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigaction
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
**Symbols:**

```
ffffffff81116ef0-ffffffff81116f01: sigset_from_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sigset_from_compat(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111ef02)
Location: kernel/compat.c:982
Inline: True
Inline callers:
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigaction
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
**Symbols:**

```
ffffffff8111e630-ffffffff8111e641: sigset_from_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sigset_from_compat(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811202a0)
Location: kernel/compat.c:512
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/signalfd.c:compat_SyS_signalfd
```
**Symbols:**

```
ffffffff811202a0-ffffffff811202b1: sigset_from_compat (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
