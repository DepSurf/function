# Function: <code>atomic_dec_and_mutex_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810c9c80)
Location: kernel/locking/mutex.c:958
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810c9c80-ffffffff810c9ce3: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ce600)
Location: kernel/locking/mutex.c:962
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810ce600-ffffffff810ce662: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810d5240)
Location: kernel/locking/mutex.c:1054
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810d5240-ffffffff810d52a2: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810d4230)
Location: kernel/locking/mutex.c:1228
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810d4230-ffffffff810d4278: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810dc190)
Location: kernel/locking/mutex.c:1228
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810dc190-ffffffff810dc1d7: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810e47d0)
Location: kernel/locking/mutex.c:1252
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810e47d0-ffffffff810e4817: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810efdc0)
Location: kernel/locking/mutex.c:1430
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810efdc0-ffffffff810efe07: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f7810)
Location: kernel/locking/mutex.c:1440
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810f7810-ffffffff810f7860: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81103640)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff81103640-ffffffff81103690: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e160)
Location: kernel/locking/mutex.c:1466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8110e160-ffffffff8110e1e5: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b420)
Location: kernel/locking/mutex.c:1469
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8110b420-ffffffff8110b4a5: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110d240)
Location: kernel/locking/mutex.c:1467
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8110d240-ffffffff8110d2c5: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8112ca80)
Location: kernel/locking/mutex.c:1080
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8112ca80-ffffffff8112caff: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8114dcd0)
Location: kernel/locking/mutex.c:1136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8114dcd0-ffffffff8114dd59: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117ce90)
Location: kernel/locking/mutex.c:1136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8117ce90-ffffffff8117cf19: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8118db40)
Location: kernel/locking/mutex.c:1136
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff8118db40-ffffffff8118dbc9: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8119c4f0)
Location: kernel/locking/mutex.c:1144
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - drivers/gpu/drm/drm_file.c:drm_release_noglobal
```
**Symbols:**

```
ffffffff8119c4f0-ffffffff8119c579: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010168830)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - drivers/perf/arm-cci.c:hw_perf_event_destroy
```
**Symbols:**

```
ffff800010168830-ffff8000101688f0: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4f38)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
  - drivers/perf/arm-cci.c:hw_perf_event_destroy
```
**Symbols:**

```
c03b4f38-c03b4fd8: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c0600)
Location: kernel/locking/mutex.c:1466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
c0000000001c0600-c0000000001c06f0: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a520)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffe00010a520-ffffffe00010a5a2: atomic_dec_and_mutex_lock (STB_GLOBAL)
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
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc950)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810fc950-ffffffff810fc9a0: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ecb60)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810ecb60-ffffffff810ecbb0: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9b10)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff810f9b10-ffffffff810f9b60: atomic_dec_and_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int atomic_dec_and_mutex_lock(atomic_t *cnt, struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104c80)
Location: kernel/locking/mutex.c:1466
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/callchain.c:put_callchain_buffers
  - fs/ecryptfs/main.c:ecryptfs_put_lower_file
```
**Symbols:**

```
ffffffff81104c80-ffffffff81104cd0: atomic_dec_and_mutex_lock (STB_GLOBAL)
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
