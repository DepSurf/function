# Function: <code>do_mq_timedreceive</code>

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
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138c560)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff8138c560-ffffffff8138caa7: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b1910)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff813b1910-ffffffff813b1e57: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1027
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff813e2460-ffffffff813e2962: do_mq_timedreceive (STB_LOCAL)
ffffffff813e3477-ffffffff813e34b5: do_mq_timedreceive.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1027
Inline: False
Direct callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff813fceb0-ffffffff813fd3bb: do_mq_timedreceive (STB_LOCAL)
ffffffff813fdc9f-ffffffff813fdcdd: do_mq_timedreceive.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1082
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff814294f0-ffffffff814299d6: do_mq_timedreceive (STB_LOCAL)
ffffffff8142a2df-ffffffff8142a30f: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff81443220-ffffffff81443706: do_mq_timedreceive (STB_LOCAL)
ffffffff8144400f-ffffffff8144403f: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1164
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff81493eb0-ffffffff814943d4: do_mq_timedreceive (STB_LOCAL)
ffffffff81494e1f-ffffffff81494e4f: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1164
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff814b1810-ffffffff814b1d34: do_mq_timedreceive (STB_LOCAL)
ffffffff81befb8c-ffffffff81befbbc: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1167
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff814b7690-ffffffff814b7bb2: do_mq_timedreceive (STB_LOCAL)
ffffffff81be1c33-ffffffff81be1c63: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81510000)
Location: ipc/mqueue.c:1169
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff81510000-ffffffff815103ca: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff815a20b0)
Location: ipc/mqueue.c:1181
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff815a20b0-ffffffff815a24cc: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8164bb80)
Location: ipc/mqueue.c:1180
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff8164bb80-ffffffff8164bf9c: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816842b0)
Location: ipc/mqueue.c:1180
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff816842b0-ffffffff816846d6: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff816c06e0)
Location: ipc/mqueue.c:1180
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff816c06e0-ffffffff816c0b1f: do_mq_timedreceive (STB_LOCAL)
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
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052aeb8)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive
```
**Symbols:**

```
ffff80001052aeb8-ffff80001052b4f4: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e31c8)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedreceive
```
**Symbols:**

```
c06e31c8-c06e3774: do_mq_timedreceive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000676650)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedreceive
```
**Symbols:**

```
c000000000676650-c000000000676dc8: do_mq_timedreceive (STB_LOCAL)
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
In ipc/mqueue.c (ffffffe00038dffc)
Location: ipc/mqueue.c:1081
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff8143b800-ffffffff8143bce6: do_mq_timedreceive (STB_LOCAL)
ffffffff8143c5ef-ffffffff8143c61f: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff8142c270-ffffffff8142c756: do_mq_timedreceive (STB_LOCAL)
ffffffff8142d05f-ffffffff8142d08f: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff814379a0-ffffffff81437e86: do_mq_timedreceive (STB_LOCAL)
ffffffff8143878f-ffffffff814387bf: do_mq_timedreceive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char *u_msg_ptr, size_t msg_len, unsigned int *u_msg_prio, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/mqueue.c (0)
Location: ipc/mqueue.c:1081
Inline: False
Direct callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
```
**Symbols:**

```
ffffffff8144df20-ffffffff8144e402: do_mq_timedreceive (STB_LOCAL)
ffffffff8144f8b7-ffffffff8144f8e7: do_mq_timedreceive.cold (STB_LOCAL)
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
