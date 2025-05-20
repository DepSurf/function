# Function: <code>do_gettimeofday</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f59d0)
Location: kernel/time/timekeeping.c:1141
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/compat.c:compat_SyS_gettimeofday
  - kernel/compat.c:compat_SyS_time
  - fs/coredump.c:do_coredump
  - drivers/input/misc/uinput.c:uinput_dev_event
```
**Symbols:**

```
ffffffff810f59d0-ffffffff810f5a55: do_gettimeofday (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fcaf0)
Location: kernel/time/timekeeping.c:1146
Inline: False
Direct callers:
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/compat.c:compat_SyS_time
  - kernel/compat.c:compat_SyS_gettimeofday
  - drivers/input/misc/uinput.c:uinput_dev_event
```
**Symbols:**

```
ffffffff810fcaf0-ffffffff810fcb75: do_gettimeofday (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ffa10)
Location: kernel/time/timekeeping.c:1175
Inline: False
Direct callers:
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/compat.c:compat_SyS_time
  - kernel/compat.c:compat_SyS_gettimeofday
  - drivers/input/misc/uinput.c:uinput_dev_event
```
**Symbols:**

```
ffffffff810ffa10-ffffffff810ffa95: do_gettimeofday (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101b50)
Location: kernel/time/timekeeping.c:1205
Inline: False
Direct callers:
  - kernel/time/time.c:compat_SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:compat_SyS_time
  - drivers/input/misc/uinput.c:uinput_dev_event
```
**Symbols:**

```
ffffffff81101b50-ffffffff81101bc9: do_gettimeofday (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110ca50)
Location: kernel/time/timekeeping.c:1209
Inline: False
Direct callers:
  - kernel/time/time.c:compat_SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:compat_SyS_time
  - drivers/input/misc/uinput.c:uinput_dev_event
```
**Symbols:**

```
ffffffff8110ca50-ffffffff8110cac9: do_gettimeofday (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval *tv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118730)
Location: kernel/time/timekeeping.c:1210
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/time.c:__x32_compat_sys_time
  - kernel/time/time.c:__ia32_compat_sys_time
```
**Symbols:**

```
ffffffff81118730-ffffffff8111879e: do_gettimeofday (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
