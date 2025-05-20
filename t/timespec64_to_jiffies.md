# Function: <code>timespec64_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810ead40)
Location: kernel/time/time.c:568
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff810ead40-ffffffff810ead99: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f19e0)
Location: kernel/time/time.c:575
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff810f19e0-ffffffff810f1a38: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8b60)
Location: kernel/time/time.c:575
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff810f8b60-ffffffff810f8bb8: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fab80)
Location: kernel/time/time.c:665
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff810fab80-ffffffff810fabd8: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105510)
Location: kernel/time/time.c:632
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81105510-ffffffff81105568: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110370)
Location: kernel/time/time.c:644
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81110370-ffffffff811103c6: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b960)
Location: kernel/time/time.c:582
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8111b960-ffffffff8111b9b6: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126390)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81126390-ffffffff811263dc: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132330)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81132330-ffffffff8113237c: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141790)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81141790-ffffffff811417e0: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d9a0)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8113d9a0-ffffffff8113d9f0: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ebf0)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8113ebf0-ffffffff8113ec3d: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162080)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81162080-ffffffff811620cd: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194fd0)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81194fd0-ffffffff81195027: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2d50)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff811d2d50-ffffffff811d2da7: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7040)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff811e7040-ffffffff811e7097: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcd90)
Location: kernel/time/time.c:617
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff811fcd90-ffffffff811fcde7: timespec64_to_jiffies (STB_GLOBAL)
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
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199d80)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffff800010199d80-ffff800010199df8: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4790)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c03e4790-c03e4858: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa030)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
c0000000001fa030-c0000000001fa0a4: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a27a)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffe00012a27a-ffffffe00012a2e6: timespec64_to_jiffies (STB_GLOBAL)
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
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112aae0)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8112aae0-ffffffff8112ab2c: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d350)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8111d350-ffffffff8111d39c: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128800)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81128800-ffffffff8112884c: timespec64_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int timespec64_to_jiffies(const struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134e80)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81134e80-ffffffff81134ecc: timespec64_to_jiffies (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *value</code> ➡️ <code>const struct timespec64 *value</code>
</li>
</ul>
</details>
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
