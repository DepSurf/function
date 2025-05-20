# Function: <code>get_compat_sigevent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811115c0)
Location: kernel/compat.c:876
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_create
  - ipc/compat_mq.c:compat_SyS_mq_notify
```
**Symbols:**

```
ffffffff811115c0-ffffffff8111165e: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118d10)
Location: kernel/compat.c:876
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_create
  - ipc/compat_mq.c:compat_SyS_mq_notify
```
**Symbols:**

```
ffffffff81118d10-ffffffff81118da6: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120430)
Location: kernel/compat.c:884
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_timer_create
  - ipc/compat_mq.c:compat_SyS_mq_notify
```
**Symbols:**

```
ffffffff81120430-ffffffff811204c6: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120dd0)
Location: kernel/compat.c:439
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - ipc/mqueue.c:compat_SyS_mq_notify
```
**Symbols:**

```
ffffffff81120dd0-ffffffff81120e66: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c430)
Location: kernel/compat.c:398
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_create
  - ipc/mqueue.c:compat_SyS_mq_notify
```
**Symbols:**

```
ffffffff8112c430-ffffffff8112c4d2: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113ac30)
Location: kernel/compat.c:363
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8113ac30-ffffffff8113acd2: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811464a0)
Location: kernel/compat.c:334
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff811464a0-ffffffff81146542: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151600)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81151600-ffffffff811516a2: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d250)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8115d250-ffffffff8115d2f2: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116dc90)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8116dc90-ffffffff8116dd32: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a270)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8116a270-ffffffff8116a324: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116af30)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8116af30-ffffffff8116afc8: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190b30)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x64_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x64_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81190b30-ffffffff81190bc8: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811c0370)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff811c0370-ffffffff811c043b: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81202720)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81202720-ffffffff812027eb: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81217b00)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81217b00-ffffffff81217bb7: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8122f6c0)
Location: kernel/compat.c:179
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff8122f6c0-ffffffff8122f777: get_compat_sigevent (STB_GLOBAL)
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
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cce08)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_compat_sys_timer_create
  - ipc/mqueue.c:__arm64_compat_sys_mq_notify
```
**Symbols:**

```
ffff8000101cce08-ffff8000101cd38c: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236f20)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_compat_sys_timer_create
  - ipc/mqueue.c:__se_compat_sys_mq_notify
```
**Symbols:**

```
c000000000236f20-c000000000237118: get_compat_sigevent (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155870)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81155870-ffffffff81155912: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148b90)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81148b90-ffffffff81148c32: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153640)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81153640-ffffffff811536e2: get_compat_sigevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_sigevent(struct sigevent *event, const struct compat_sigevent *u_event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160540)
Location: kernel/compat.c:267
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_create
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_create
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
**Symbols:**

```
ffffffff81160540-ffffffff811605e2: get_compat_sigevent (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
