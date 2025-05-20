# Function: <code>compat_SyS_timerfd_settime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_timerfd_settime(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81258e10)
Location: fs/timerfd.c:542
Inline: False
```
**Symbols:**

```
ffffffff81258e10-ffffffff81258eaa: compat_SyS_timerfd_settime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_timerfd_settime(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812817f0)
Location: fs/timerfd.c:552
Inline: False
```
**Symbols:**

```
ffffffff812817f0-ffffffff8128188a: compat_SyS_timerfd_settime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_timerfd_settime(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81295320)
Location: fs/timerfd.c:552
Inline: False
```
**Symbols:**

```
ffffffff81295320-ffffffff812953ba: compat_SyS_timerfd_settime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_timerfd_settime(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812a25a0)
Location: fs/timerfd.c:562
Inline: False
```
**Symbols:**

```
ffffffff812a25a0-ffffffff812a2648: compat_SyS_timerfd_settime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_timerfd_settime(long int ufd, long int flags, long int utmr, long int otmr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812c58c0)
Location: fs/timerfd.c:563
Inline: False
```
**Symbols:**

```
ffffffff812c58c0-ffffffff812c5968: compat_SyS_timerfd_settime (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
