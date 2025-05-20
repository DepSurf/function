# Function: <code>mark_wakeup_next_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822901)
Location: kernel/locking/rtmutex.c:976
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189ce26)
Location: kernel/locking/rtmutex.c:974
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d1d02)
Location: kernel/locking/rtmutex.c:1038
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5240)
Location: kernel/locking/rtmutex.c:1030
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810d5240-ffffffff810d52d9: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dd0d0)
Location: kernel/locking/rtmutex.c:1018
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810dd0d0-ffffffff810dd187: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e5770)
Location: kernel/locking/rtmutex.c:1018
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810e5770-ffffffff810e5833: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f0d00)
Location: kernel/locking/rtmutex.c:1018
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810f0d00-ffffffff810f0dc3: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f9460)
Location: kernel/locking/rtmutex.c:1019
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810f9460-ffffffff810f9554: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105250)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff81105250-ffffffff81105344: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110010)
Location: kernel/locking/rtmutex.c:1015
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff81110010-ffffffff81110102: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110d1c0)
Location: kernel/locking/rtmutex.c:1015
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff8110d1c0-ffffffff8110d2b2: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c35c80)
Location: kernel/locking/rtmutex.c:989
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81c35c80-ffffffff81c35d72: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head *wqh, struct rt_mutex_base *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54480)
Location: kernel/locking/rtmutex.c:1182
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81d54480-ffffffff81d54572: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head *wqh, struct rt_mutex_base *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f25fa0)
Location: kernel/locking/rtmutex.c:1194
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff81f25fa0-ffffffff81f260a1: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head *wqh, struct rt_mutex_base *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d1a50)
Location: kernel/locking/rtmutex.c:1232
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff820d1a50-ffffffff820d1b51: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head *wqh, struct rt_mutex_base *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82155dc0)
Location: kernel/locking/rtmutex.c:1288
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff82155dc0-ffffffff82155eb1: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct rt_wake_q_head *wqh, struct rt_mutex_base *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82238c00)
Location: kernel/locking/rtmutex.c:1307
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
**Symbols:**

```
ffffffff82238c00-ffffffff82238cf1: mark_wakeup_next_waiter (STB_LOCAL)
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
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016aef8)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffff80001016aef8-ffff80001016b028: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b6b08)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
c03b6b08-c03b6c28: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c27d0)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
c0000000001c27d0-c0000000001c2930: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010b53a)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffe00010b53a-ffffffe00010b632: mark_wakeup_next_waiter (STB_LOCAL)
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
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fe560)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810fe560-ffffffff810fe654: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ee760)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810ee760-ffffffff810ee854: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fb720)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff810fb720-ffffffff810fb814: mark_wakeup_next_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mark_wakeup_next_waiter(struct wake_q_head *wake_q, struct rt_mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811068f0)
Location: kernel/locking/rtmutex.c:1017
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
**Symbols:**

```
ffffffff811068f0-ffffffff811069e9: mark_wakeup_next_waiter (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rt_wake_q_head *wqh</code>
</li>
<li>
<b>Param removed. </b>
<code>struct wake_q_head *wake_q</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex *lock</code> ➡️ <code>struct rt_mutex_base *lock</code>
</li>
</ul>
</details>
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
