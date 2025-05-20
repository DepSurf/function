# Function: <code>common_nsleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, struct timespec *tsave, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0d00)
Location: kernel/time/posix-timers.c:1089
Inline: False
```
**Symbols:**

```
ffffffff810f0d00-ffffffff810f0d27: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, struct timespec *tsave, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7d20)
Location: kernel/time/posix-timers.c:1089
Inline: False
```
**Symbols:**

```
ffffffff810f7d20-ffffffff810f7d46: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, struct timespec *tsave, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811056c0)
Location: kernel/time/posix-timers.c:1089
Inline: False
```
**Symbols:**

```
ffffffff811056c0-ffffffff811056e6: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811075d0)
Location: kernel/time/posix-timers.c:1191
Inline: False
```
**Symbols:**

```
ffffffff811075d0-ffffffff811075ec: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112710)
Location: kernel/time/posix-timers.c:1197
Inline: False
```
**Symbols:**

```
ffffffff81112710-ffffffff8111272c: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e1a0)
Location: kernel/time/posix-timers.c:1214
Inline: False
```
**Symbols:**

```
ffffffff8111e1a0-ffffffff8111e1bc: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811299f0)
Location: kernel/time/posix-timers.c:1180
Inline: False
```
**Symbols:**

```
ffffffff811299f0-ffffffff81129a0c: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81134470)
Location: kernel/time/posix-timers.c:1165
Inline: False
```
**Symbols:**

```
ffffffff81134470-ffffffff8113448e: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81140480)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffff81140480-ffffffff8114049e: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f630)
Location: kernel/time/posix-timers.c:1222
Inline: False
```
**Symbols:**

```
ffffffff8114f630-ffffffff8114f676: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b8b0)
Location: kernel/time/posix-timers.c:1222
Inline: False
```
**Symbols:**

```
ffffffff8114b8b0-ffffffff8114b8f6: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cd60)
Location: kernel/time/posix-timers.c:1222
Inline: False
```
**Symbols:**

```
ffffffff8114cd60-ffffffff8114cda6: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170da0)
Location: kernel/time/posix-timers.c:1222
Inline: False
```
**Symbols:**

```
ffffffff81170da0-ffffffff81170de6: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5420)
Location: kernel/time/posix-timers.c:1231
Inline: False
```
**Symbols:**

```
ffffffff811a5420-ffffffff811a5474: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4de0)
Location: kernel/time/posix-timers.c:1231
Inline: False
```
**Symbols:**

```
ffffffff811e4de0-ffffffff811e4e34: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9440)
Location: kernel/time/posix-timers.c:1345
Inline: False
```
**Symbols:**

```
ffffffff811f9440-ffffffff811f9494: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f630)
Location: kernel/time/posix-timers.c:1345
Inline: False
```
**Symbols:**

```
ffffffff8120f630-ffffffff8120f684: common_nsleep (STB_LOCAL)
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
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101aa7e0)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffff8000101aa7e0-ffff8000101aa828: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5d4c)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
c03f5d4c-c03f5d7c: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020e2a0)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
c00000000020e2a0-c00000000020e2ec: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000135be6)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffe000135be6-ffffffe000135c26: common_nsleep (STB_LOCAL)
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
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138c30)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffff81138c30-ffffffff81138c4e: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b680)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffff8112b680-ffffffff8112b69e: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136950)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffff81136950-ffffffff8113696e: common_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int common_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811433e0)
Location: kernel/time/posix-timers.c:1200
Inline: False
```
**Symbols:**

```
ffffffff811433e0-ffffffff811433fe: common_nsleep (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct timespec *rqtp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec *tsave</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec *rmtp</code>
</li>
</ul>
</details>
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
<code>const struct timespec *rqtp</code> ➡️ <code>const struct timespec64 *rqtp</code>
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
