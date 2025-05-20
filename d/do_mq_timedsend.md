# Function: <code>do_mq_timedsend</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138bc80)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8138bc80-ffffffff8138c011: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b1030)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff813b1030-ffffffff813b13c1: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e1e10)
Location: ipc/mqueue.c:909
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff813e1e10-ffffffff813e21a0: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fc860)
Location: ipc/mqueue.c:909
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff813fc860-ffffffff813fcbf0: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81428800)
Location: ipc/mqueue.c:964
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81428800-ffffffff81428b99: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81442530)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81442530-ffffffff814428c9: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81492df0)
Location: ipc/mqueue.c:1044
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81492df0-ffffffff814931d0: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b06f0)
Location: ipc/mqueue.c:1044
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff814b06f0-ffffffff814b0ad0: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814b6540)
Location: ipc/mqueue.c:1047
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff814b6540-ffffffff814b6935: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8150ee80)
Location: ipc/mqueue.c:1049
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff8150ee80-ffffffff8150f275: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a1930)
Location: ipc/mqueue.c:1061
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff815a1930-ffffffff815a1d6f: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164b3b0)
Location: ipc/mqueue.c:1060
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff8164b3b0-ffffffff8164b7ef: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81683ac0)
Location: ipc/mqueue.c:1060
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81683ac0-ffffffff81683f1a: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816bfee0)
Location: ipc/mqueue.c:1061
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff816bfee0-ffffffff816c0348: do_mq_timedsend (STB_LOCAL)
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
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052b688)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedsend
```
**Symbols:**

```
ffff80001052b688-ffff80001052ba20: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e3774)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
**Symbols:**

```
c06e3774-c06e3c54: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000676fd0)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
**Symbols:**

```
c000000000676fd0-c00000000067747c: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038dcf0)
Location: ipc/mqueue.c:963
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143ab10)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff8143ab10-ffffffff8143aea9: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142b580)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff8142b580-ffffffff8142b919: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81436cb0)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81436cb0-ffffffff81437049: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char *u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144d230)
Location: ipc/mqueue.c:963
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff8144d230-ffffffff8144d5d9: do_mq_timedsend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
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
