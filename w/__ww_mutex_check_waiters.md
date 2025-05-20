# Function: <code>__ww_mutex_check_waiters</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29270)
Location: kernel/locking/mutex.c:417
Inline: False
```
**Symbols:**

```
ffffffff81a29270-ffffffff81a292f5: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a99900)
Location: kernel/locking/mutex.c:418
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81a99900-ffffffff81a99985: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1250)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81ad1250-ffffffff81ad12d5: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bc9410)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81bc9410-ffffffff81bc94be: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c42230)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81c42230-ffffffff81c422de: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c341a0)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81c341a0-ffffffff81c3424e: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8112c910)
Location: kernel/locking/ww_mutex.h:355
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff8112c910-ffffffff8112c9d2: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8114da70)
Location: kernel/locking/ww_mutex.h:355
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
```
**Symbols:**

```
ffffffff8114da70-ffffffff8114db96: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117cb10)
Location: kernel/locking/ww_mutex.h:355
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
```
**Symbols:**

```
ffffffff8117cb10-ffffffff8117cc36: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8118d8f0)
Location: kernel/locking/ww_mutex.h:355
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
```
**Symbols:**

```
ffffffff8118d8f0-ffffffff8118da16: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8119c2a0)
Location: kernel/locking/ww_mutex.h:355
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_trylock
```
**Symbols:**

```
ffffffff8119c2a0-ffffffff8119c3c6: __ww_mutex_check_waiters (STB_LOCAL)
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
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da2c78)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffff800010da2c78-ffff800010da2d2c: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9b66c)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
c0e9b66c-c0e9b700: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee52b0)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
c000000000ee52b0-c000000000ee53bc: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c6940)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffe0008c6940-ffffffe0008c69d2: __ww_mutex_check_waiters (STB_LOCAL)
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
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a700c0)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81a700c0-ffffffff81a70145: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2c4b0)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81a2c4b0-ffffffff81a2c535: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81adc4d0)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81adc4d0-ffffffff81adc555: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ww_mutex_check_waiters(struct mutex *lock, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae8b30)
Location: kernel/locking/mutex.c:444
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
**Symbols:**

```
ffffffff81ae8b30-ffffffff81ae8bb5: __ww_mutex_check_waiters (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
