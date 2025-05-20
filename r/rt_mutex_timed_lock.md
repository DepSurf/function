# Function: <code>rt_mutex_timed_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb6a0)
Location: kernel/locking/rtmutex.c:1449
Inline: False
```
**Symbols:**

```
ffffffff810cb6a0-ffffffff810cb6f1: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d0100)
Location: kernel/locking/rtmutex.c:1458
Inline: False
```
**Symbols:**

```
ffffffff810d0100-ffffffff810d0151: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6af0)
Location: kernel/locking/rtmutex.c:1522
Inline: False
```
**Symbols:**

```
ffffffff810d6af0-ffffffff810d6b41: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5b90)
Location: kernel/locking/rtmutex.c:1534
Inline: True
```
**Symbols:**

```
ffffffff810d5b90-ffffffff810d5be1: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ddb50)
Location: kernel/locking/rtmutex.c:1534
Inline: True
```
**Symbols:**

```
ffffffff810ddb50-ffffffff810ddba1: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e61b0)
Location: kernel/locking/rtmutex.c:1554
Inline: True
```
**Symbols:**

```
ffffffff810e61b0-ffffffff810e61fe: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1730)
Location: kernel/locking/rtmutex.c:1554
Inline: True
```
**Symbols:**

```
ffffffff810f1730-ffffffff810f177e: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa000)
Location: kernel/locking/rtmutex.c:1555
Inline: True
```
**Symbols:**

```
ffffffff810fa000-ffffffff810fa059: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105df0)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffff81105df0-ffffffff81105e49: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110d40)
Location: kernel/locking/rtmutex.c:1551
Inline: False
```
**Symbols:**

```
ffffffff81110d40-ffffffff81110d99: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110def0)
Location: kernel/locking/rtmutex.c:1551
Inline: False
```
**Symbols:**

```
ffffffff8110def0-ffffffff8110df49: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016bf08)
Location: kernel/locking/rtmutex.c:1553
Inline: False
```
**Symbols:**

```
ffff80001016bf08-ffff80001016bf98: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b78b8)
Location: kernel/locking/rtmutex.c:1553
Inline: False
```
**Symbols:**

```
c03b78b8-c03b7928: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3a70)
Location: kernel/locking/rtmutex.c:1553
Inline: False
```
**Symbols:**

```
c0000000001c3a70-c0000000001c3b18: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c1ce)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffe00010c1ce-ffffffe00010c230: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff100)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffff810ff100-ffffffff810ff159: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef2f0)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffff810ef2f0-ffffffff810ef349: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc2c0)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffff810fc2c0-ffffffff810fc319: rt_mutex_timed_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rt_mutex_timed_lock(struct rt_mutex *lock, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107500)
Location: kernel/locking/rtmutex.c:1553
Inline: True
```
**Symbols:**

```
ffffffff81107500-ffffffff81107537: rt_mutex_timed_lock (STB_GLOBAL)
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
