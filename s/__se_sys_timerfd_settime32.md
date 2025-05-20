# Function: <code>__se_sys_timerfd_settime32</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132459d)
Location: fs/timerfd.c:563
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813372fd)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81371228)
Location: fs/timerfd.c:570
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8137efa8)
Location: fs/timerfd.c:570
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81385c2d)
Location: fs/timerfd.c:570
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813d2d7d)
Location: fs/timerfd.c:586
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
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
In fs/timerfd.c (ffffffff8145b65d)
Location: fs/timerfd.c:586
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
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
In fs/timerfd.c (ffffffff814eac8d)
Location: fs/timerfd.c:586
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
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
In fs/timerfd.c (ffffffff81521a2d)
Location: fs/timerfd.c:586
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
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
In fs/timerfd.c (ffffffff8155606d)
Location: fs/timerfd.c:586
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
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
In fs/timerfd.c (ffff8000103f51e8)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__arm64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_timerfd_settime32(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c05ca398)
Location: fs/timerfd.c:567
Inline: False
```
**Symbols:**

```
c05ca398-c05ca44c: __se_sys_timerfd_settime32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_timerfd_settime32(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c0000000004fd3e0)
Location: fs/timerfd.c:567
Inline: False
```
**Symbols:**

```
c0000000004fd3e0-c0000000004fd4c0: __se_sys_timerfd_settime32 (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132f8dd)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813204fd)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132d3ad)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8133fe9d)
Location: fs/timerfd.c:567
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
