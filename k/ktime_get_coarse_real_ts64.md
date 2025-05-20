# Function: <code>ktime_get_coarse_real_ts64</code>

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
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117620)
Location: kernel/time/timekeeping.c:2136
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff81117620-ffffffff81117661: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122c40)
Location: kernel/time/timekeeping.c:2150
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81122c40-ffffffff81122c81: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d290)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff8112d290-ffffffff8112d2d0: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139230)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81139230-ffffffff81139270: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147e80)
Location: kernel/time/timekeeping.c:2159
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81147e80-ffffffff81147ec2: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811442b0)
Location: kernel/time/timekeeping.c:2222
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff811442b0-ffffffff811442f1: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145440)
Location: kernel/time/timekeeping.c:2233
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81145440-ffffffff81145481: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2234
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81cb0c4c-ffffffff81cb0c6c: ktime_get_coarse_real_ts64.cold (STB_LOCAL)
ffffffff811696d0-ffffffff8116972a: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2255
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_entry
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff81e621e4-ffffffff81e62204: ktime_get_coarse_real_ts64.cold (STB_LOCAL)
ffffffff8119d390-ffffffff8119d3f8: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2255
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_entry
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff8205b031-ffffffff8205b051: ktime_get_coarse_real_ts64.cold (STB_LOCAL)
ffffffff811dbea0-ffffffff811dbf08: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2255
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_entry
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff820d9883-ffffffff820d98a3: ktime_get_coarse_real_ts64.cold (STB_LOCAL)
ffffffff811f0140-ffffffff811f01a8: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2255
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_entry
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:inode_update_timestamps
  - fs/inode.c:inode_update_timestamps
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff821b5182-ffffffff821b51a2: ktime_get_coarse_real_ts64.cold (STB_LOCAL)
ffffffff81206280-ffffffff812062e8: ktime_get_coarse_real_ts64 (STB_GLOBAL)
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
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2dc8)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffff8000101a2dc8-ffff8000101a2e2c: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ecac4)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
c03ecac4-c03ecb64: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204310)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
c000000000204310-c00000000020437c: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fab0)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffe00012fab0-ffffffe00012fb04: ktime_get_coarse_real_ts64 (STB_GLOBAL)
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
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811319e0)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff811319e0-ffffffff81131a20: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124440)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff81124440-ffffffff81124480: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f700)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff8112f700-ffffffff8112f740: ktime_get_coarse_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ktime_get_coarse_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c120)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
```
**Symbols:**

```
ffffffff8113c120-ffffffff8113c160: ktime_get_coarse_real_ts64 (STB_GLOBAL)
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
