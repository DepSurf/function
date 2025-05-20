# Function: <code>rt_mutex_slowunlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822890)
Location: kernel/locking/rtmutex.c:1263
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
```
**Symbols:**

```
ffffffff81822890-ffffffff81822977: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189cda0)
Location: kernel/locking/rtmutex.c:1269
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff8189cda0-ffffffff8189ce95: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d1c80)
Location: kernel/locking/rtmutex.c:1333
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff818d1c80-ffffffff818d1d6f: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81908e50)
Location: kernel/locking/rtmutex.c:1345
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81908e50-ffffffff81908efd: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81992f60)
Location: kernel/locking/rtmutex.c:1340
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81992f60-ffffffff8199300d: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef540)
Location: kernel/locking/rtmutex.c:1339
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff819ef540-ffffffff819ef5ed: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2a880)
Location: kernel/locking/rtmutex.c:1339
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81a2a880-ffffffff81a2a92d: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b570)
Location: kernel/locking/rtmutex.c:1340
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81a9b570-ffffffff81a9b627: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad2ec0)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81ad2ec0-ffffffff81ad2f77: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcaf70)
Location: kernel/locking/rtmutex.c:1336
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81bcaf70-ffffffff81bcb027: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c43e00)
Location: kernel/locking/rtmutex.c:1336
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81c43e00-ffffffff81c43eb7: rt_mutex_slowunlock (STB_LOCAL)
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
In kernel/locking/rtmutex.c (ffffffff81c35df3)
Location: kernel/locking/rtmutex.c:1312
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff81d545ec)
Location: kernel/locking/rtmutex.c:1279
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff81f26128)
Location: kernel/locking/rtmutex.c:1291
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff820d1be8)
Location: kernel/locking/rtmutex.c:1329
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff82155f48)
Location: kernel/locking/rtmutex.c:1387
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rtmutex_api.c (ffffffff82238d88)
Location: kernel/locking/rtmutex.c:1406
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5660)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffff800010da5660-ffff800010da5800: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d5d8)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
c0e9d5d8-c0e9d68c: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee7ce0)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
c000000000ee7ce0-c000000000ee7e18: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c7fb0)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffe0008c7fb0-ffffffe0008c805c: rt_mutex_slowunlock (STB_LOCAL)
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
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a71d30)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81a71d30-ffffffff81a71de7: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e100)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81a2e100-ffffffff81a2e1b7: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade140)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81ade140-ffffffff81ade1f7: rt_mutex_slowunlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rt_mutex_slowunlock(struct rt_mutex *lock, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea5e0)
Location: kernel/locking/rtmutex.c:1338
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81aea5e0-ffffffff81aea697: rt_mutex_slowunlock (STB_LOCAL)
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
