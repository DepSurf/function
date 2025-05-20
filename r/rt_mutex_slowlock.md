# Function: <code>rt_mutex_slowlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822b10)
Location: kernel/locking/rtmutex.c:1170
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
```
**Symbols:**

```
ffffffff81822b10-ffffffff81822cec: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189d060)
Location: kernel/locking/rtmutex.c:1166
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff8189d060-ffffffff8189d23f: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d1f40)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff818d1f40-ffffffff818d2134: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909110)
Location: kernel/locking/rtmutex.c:1243
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81909110-ffffffff819092fb: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993230)
Location: kernel/locking/rtmutex.c:1231
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81993230-ffffffff8199341b: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef810)
Location: kernel/locking/rtmutex.c:1231
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff819ef810-ffffffff819ef9f0: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2ab60)
Location: kernel/locking/rtmutex.c:1231
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81a2ab60-ffffffff81a2ad40: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b850)
Location: kernel/locking/rtmutex.c:1232
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81a9b850-ffffffff81a9ba29: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad31a0)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81ad31a0-ffffffff81ad3379: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb260)
Location: kernel/locking/rtmutex.c:1228
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81bcb260-ffffffff81bcb470: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c44100)
Location: kernel/locking/rtmutex.c:1228
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81c44100-ffffffff81c44310: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c370b0)
Location: kernel/locking/rtmutex.c:1193
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81c370b0-ffffffff81c37226: rt_mutex_slowlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d559e0)
Location: kernel/locking/rtmutex.c:1621
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81d559e0-ffffffff81d55b31: rt_mutex_slowlock.constprop.0 (STB_LOCAL)
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
In kernel/locking/rtmutex_api.c (ffffffff81f27988)
Location: kernel/locking/rtmutex.c:1637
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff820d3478)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff82157750)
Location: kernel/locking/rtmutex.c:1733
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
In kernel/locking/rtmutex_api.c (ffffffff8223a5a0)
Location: kernel/locking/rtmutex.c:1752
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
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
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5b60)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffff800010da5b60-ffff800010da5d68: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d9ac)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
c0e9d9ac-c0e9dba4: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee81f0)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
c000000000ee81f0-c000000000ee8408: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c825c)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffe0008c825c-ffffffe0008c8394: rt_mutex_slowlock (STB_LOCAL)
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
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a72010)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81a72010-ffffffff81a721e9: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e3e0)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81a2e3e0-ffffffff81a2e5b9: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade420)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81ade420-ffffffff81ade5f9: rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea8d0)
Location: kernel/locking/rtmutex.c:1230
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81aea8d0-ffffffff81aeaaa9: rt_mutex_slowlock (STB_LOCAL)
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
