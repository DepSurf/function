# Function: <code>__ww_mutex_wound</code>

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
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810efca0)
Location: kernel/locking/mutex.c:362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff810efca0-ffffffff810efd01: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f7700)
Location: kernel/locking/mutex.c:363
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff810f7700-ffffffff810f776a: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff811034c0)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff811034c0-ffffffff8110352a: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bc9463)
Location: kernel/locking/mutex.c:389
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c42283)
Location: kernel/locking/mutex.c:389
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff81c341f3)
Location: kernel/locking/mutex.c:389
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff8112c984)
Location: kernel/locking/ww_mutex.h:300
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff8114db16)
Location: kernel/locking/ww_mutex.h:300
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff8117cbb6)
Location: kernel/locking/ww_mutex.h:300
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff8118d996)
Location: kernel/locking/ww_mutex.h:300
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
In kernel/locking/mutex.c (ffffffff8119c346)
Location: kernel/locking/ww_mutex.h:300
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
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
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff8000101686d8)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffff8000101686d8-ffff80001016877c: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4df4)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
c03b4df4-c03b4e88: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c03a0)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
c0000000001c03a0-c0000000001c0454: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a44a)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffe00010a44a-ffffffe00010a4ac: __ww_mutex_wound (STB_LOCAL)
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
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc7d0)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff810fc7d0-ffffffff810fc83a: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ec9e0)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff810ec9e0-ffffffff810eca4a: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9990)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff810f9990-ffffffff810f99fa: __ww_mutex_wound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __ww_mutex_wound(struct mutex *lock, struct ww_acquire_ctx *ww_ctx, struct ww_acquire_ctx *hold_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104af0)
Location: kernel/locking/mutex.c:389
Inline: False
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
```
**Symbols:**

```
ffffffff81104af0-ffffffff81104b5a: __ww_mutex_wound (STB_LOCAL)
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
