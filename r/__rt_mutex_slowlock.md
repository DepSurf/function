# Function: <code>__rt_mutex_slowlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822a30)
Location: kernel/locking/rtmutex.c:1107
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
```
**Symbols:**

```
ffffffff81822a30-ffffffff81822b0e: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189cf70)
Location: kernel/locking/rtmutex.c:1103
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff8189cf70-ffffffff8189d053: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d1e50)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff818d1e50-ffffffff818d1f31: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909030)
Location: kernel/locking/rtmutex.c:1180
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81909030-ffffffff8190910d: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993140)
Location: kernel/locking/rtmutex.c:1168
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81993140-ffffffff81993222: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef720)
Location: kernel/locking/rtmutex.c:1168
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff819ef720-ffffffff819ef805: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2aa70)
Location: kernel/locking/rtmutex.c:1168
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81a2aa70-ffffffff81a2ab55: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b770)
Location: kernel/locking/rtmutex.c:1169
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81a9b770-ffffffff81a9b84f: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad30c0)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81ad30c0-ffffffff81ad319f: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb0b0)
Location: kernel/locking/rtmutex.c:1165
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81bcb0b0-ffffffff81bcb188: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c43f40)
Location: kernel/locking/rtmutex.c:1165
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81c43f40-ffffffff81c44024: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c36090)
Location: kernel/locking/rtmutex.c:1138
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
```
**Symbols:**

```
ffffffff81c36090-ffffffff81c36160: __rt_mutex_slowlock (STB_LOCAL)
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
In kernel/locking/rtmutex_api.c (ffffffff81d55a53)
Location: kernel/locking/rtmutex.c:1550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f276a0)
Location: kernel/locking/rtmutex.c:1561
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff81f276a0-ffffffff81f27856: __rt_mutex_slowlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3180)
Location: kernel/locking/rtmutex.c:1599
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
**Symbols:**

```
ffffffff820d3180-ffffffff820d3330: __rt_mutex_slowlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821574d0)
Location: kernel/locking/rtmutex.c:1657
Inline: True
```
**Symbols:**

```
ffffffff821574d0-ffffffff82157680: __rt_mutex_slowlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a310)
Location: kernel/locking/rtmutex.c:1676
Inline: True
```
**Symbols:**

```
ffffffff8223a310-ffffffff8223a4c0: __rt_mutex_slowlock.constprop.0 (STB_LOCAL)
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
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da58c0)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffff800010da58c0-ffff800010da5a28: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d758)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c0e9d758-c0e9d888: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee7f00)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c000000000ee7f00-c000000000ee80b0: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c817c)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffe0008c817c-ffffffe0008c825c: __rt_mutex_slowlock (STB_LOCAL)
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
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a71f30)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81a71f30-ffffffff81a7200f: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e300)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81a2e300-ffffffff81a2e3d9: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade340)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81ade340-ffffffff81ade41f: __rt_mutex_slowlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __rt_mutex_slowlock(struct rt_mutex *lock, int state, struct hrtimer_sleeper *timeout, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea7f0)
Location: kernel/locking/rtmutex.c:1167
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81aea7f0-ffffffff81aea8c7: __rt_mutex_slowlock (STB_LOCAL)
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
