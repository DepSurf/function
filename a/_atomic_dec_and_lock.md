# Function: <code>_atomic_dec_and_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff813e9300)
Location: lib/dec_and_lock.c:20
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff813e9300-ffffffff813e9360: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8142f510)
Location: lib/dec_and_lock.c:20
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8142f510-ffffffff8142f56f: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8144b740)
Location: lib/dec_and_lock.c:20
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8144b740-ffffffff8144b79f: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff818ebe00)
Location: lib/dec_and_lock.c:20
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff818ebe00-ffffffff818ebe43: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81971df0)
Location: lib/dec_and_lock.c:21
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff81971df0-ffffffff81971e37: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff819ce1b0)
Location: lib/dec_and_lock.c:21
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff819ce1b0-ffffffff819ce1f7: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a07670)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81a07670-ffffffff81a076b7: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a76fe0)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81a76fe0-ffffffff81a77034: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81aae3c0)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81aae3c0-ffffffff81aae414: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff815e80e0)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff815e80e0-ffffffff815e8134: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8160d2a0)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff8160d2a0-ffffffff8160d2f4: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff815f0a00)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff815f0a00-ffffffff815f0a54: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8165db40)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff8165db40-ffffffff8165db94: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81777160)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff81777160-ffffffff817771b5: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8201faf0)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
```
**Symbols:**

```
ffffffff8201faf0-ffffffff8201fb45: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8209fa00)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
```
**Symbols:**

```
ffffffff8209fa00-ffffffff8209fa55: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff821779d0)
Location: lib/dec_and_lock.c:21
Inline: False
Direct callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_open
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
```
**Symbols:**

```
ffffffff821779d0-ffffffff82177a25: _atomic_dec_and_lock (STB_GLOBAL)
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
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffff800010d84708)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffff800010d84708-ffff800010d84800: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (c0e7fbd0)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
c0e7fbd0-c0e7fc7c: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (c000000000ec3b10)
Location: lib/dec_and_lock.c:21
Inline: False
```
**Symbols:**

```
c000000000ec3b10-c000000000ec3c40: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffe0008aebac)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffe0008aebac-ffffffe0008aec5c: _atomic_dec_and_lock (STB_GLOBAL)
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
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a4d210)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81a4d210-ffffffff81a4d264: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a0a340)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81a0a340-ffffffff81a0a394: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81ab9600)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81ab9600-ffffffff81ab9654: _atomic_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock(atomic_t *atomic, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81ac5a50)
Location: lib/dec_and_lock.c:21
Inline: True
```
**Symbols:**

```
ffffffff81ac5a50-ffffffff81ac5aa2: _atomic_dec_and_lock (STB_GLOBAL)
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
