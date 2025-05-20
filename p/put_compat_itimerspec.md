# Function: <code>put_compat_itimerspec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_itimerspec(struct compat_itimerspec *dst, const struct itimerspec *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81111140)
Location: kernel/compat.c:673
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_settime
  - kernel/compat.c:compat_SyS_timer_gettime
  - fs/timerfd.c:compat_SyS_timerfd_settime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
```
**Symbols:**

```
ffffffff81111140-ffffffff81111182: put_compat_itimerspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_itimerspec(struct compat_itimerspec *dst, const struct itimerspec *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118870)
Location: kernel/compat.c:673
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_gettime
  - kernel/compat.c:compat_SyS_timer_settime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:compat_SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81118870-ffffffff811188b2: put_compat_itimerspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_itimerspec(struct compat_itimerspec *dst, const struct itimerspec *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111ff90)
Location: kernel/compat.c:681
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_gettime
  - kernel/compat.c:compat_SyS_timer_settime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:compat_SyS_timerfd_settime
```
**Symbols:**

```
ffffffff8111ff90-ffffffff8111ffd2: put_compat_itimerspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_itimerspec(struct compat_itimerspec *dst, const struct itimerspec *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120d90)
Location: kernel/compat.c:402
Inline: False
```
**Symbols:**

```
ffffffff81120d90-ffffffff81120dcf: put_compat_itimerspec (STB_GLOBAL)
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
