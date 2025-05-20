# Function: <code>ww_mutex_lock_interruptible</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81908900)
Location: kernel/locking/mutex.c:1205
Inline: True
```
**Symbols:**

```
ffffffff81907950-ffffffff8190798e: ww_mutex_lock_interruptible.part.5 (STB_LOCAL)
ffffffff81908900-ffffffff81908969: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819929a0)
Location: kernel/locking/mutex.c:1205
Inline: True
```
**Symbols:**

```
ffffffff81991a40-ffffffff81991a7e: ww_mutex_lock_interruptible.part.5 (STB_LOCAL)
ffffffff819929a0-ffffffff81992a0c: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee9c0)
Location: kernel/locking/mutex.c:1229
Inline: True
```
**Symbols:**

```
ffffffff819ee270-ffffffff819ee2cd: ww_mutex_lock_interruptible.part.8 (STB_LOCAL)
ffffffff819ee9c0-ffffffff819eea03: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29d20)
Location: kernel/locking/mutex.c:1407
Inline: True
```
**Symbols:**

```
ffffffff81a294e0-ffffffff81a2953d: ww_mutex_lock_interruptible.part.13 (STB_LOCAL)
ffffffff81a29d20-ffffffff81a29d63: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9a430)
Location: kernel/locking/mutex.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81a9a430-ffffffff81a9a4bd: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1d80)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81ad1d80-ffffffff81ad1e0d: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bc9e50)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81bc9e50-ffffffff81bc9edb: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c42ca0)
Location: kernel/locking/mutex.c:1446
Inline: False
```
**Symbols:**

```
ffffffff81c42ca0-ffffffff81c42d2b: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c35300)
Location: kernel/locking/mutex.c:1444
Inline: False
```
**Symbols:**

```
ffffffff81c35300-ffffffff81c3538b: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d53b00)
Location: kernel/locking/mutex.c:1056
Inline: False
```
**Symbols:**

```
ffffffff81d53b00-ffffffff81d53b8b: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f241a0)
Location: kernel/locking/mutex.c:1112
Inline: False
```
**Symbols:**

```
ffffffff81f241a0-ffffffff81f24237: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820cf690)
Location: kernel/locking/mutex.c:1112
Inline: False
```
**Symbols:**

```
ffffffff820cf690-ffffffff820cf727: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82154400)
Location: kernel/locking/mutex.c:1112
Inline: False
```
**Symbols:**

```
ffffffff82154400-ffffffff82154497: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82237240)
Location: kernel/locking/mutex.c:1117
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_lock_single_interruptible
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_pin
```
**Symbols:**

```
ffffffff82237240-ffffffff822372d7: ww_mutex_lock_interruptible (STB_GLOBAL)
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
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da41f0)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffff800010da41f0-ffff800010da42f4: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9bfe8)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
c0e9bfe8-c0e9c0b8: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee6b40)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
c000000000ee6b40-c000000000ee6c64: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c75da)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffe0008c75da-ffffffe0008c76ac: ww_mutex_lock_interruptible (STB_GLOBAL)
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
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a70bf0)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81a70bf0-ffffffff81a70c7d: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2cfe0)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81a2cfe0-ffffffff81a2d06d: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add000)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81add000-ffffffff81add08d: ww_mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ww_mutex_lock_interruptible(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae9b30)
Location: kernel/locking/mutex.c:1443
Inline: False
```
**Symbols:**

```
ffffffff81ae9b30-ffffffff81ae9bb3: ww_mutex_lock_interruptible (STB_GLOBAL)
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
