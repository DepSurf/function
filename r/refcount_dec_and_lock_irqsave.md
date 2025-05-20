# Function: <code>refcount_dec_and_lock_irqsave</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814cda80)
Location: lib/refcount.c:366
Inline: True
```
**Symbols:**

```
ffffffff814cda80-ffffffff814cdad3: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e2350)
Location: lib/refcount.c:365
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff814e2350-ffffffff814e23a3: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e1f0)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8150e1f0-ffffffff8150e259: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152c040)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8152c040-ffffffff8152c0a9: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8158f940)
Location: lib/refcount.c:172
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8158f940-ffffffff8158f9d1: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815ac470)
Location: lib/refcount.c:172
Inline: True
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff815ac470-ffffffff815ac501: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815b7140)
Location: lib/refcount.c:172
Inline: True
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff815b7140-ffffffff815b71d1: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/refcount.c (ffffffff8161d7a2)
Location: lib/refcount.c:172
Inline: True
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff81cdadf6-ffffffff81cdae0a: refcount_dec_and_lock_irqsave.cold (STB_LOCAL)
ffffffff8161d770-ffffffff8161d80d: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:172
Inline: False
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff81e936c6-ffffffff81e936da: refcount_dec_and_lock_irqsave.cold (STB_LOCAL)
ffffffff816eb300-ffffffff816eb39d: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:172
Inline: False
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff8207888e-ffffffff820788a2: refcount_dec_and_lock_irqsave.cold (STB_LOCAL)
ffffffff817db9b0-ffffffff817dba4d: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:172
Inline: False
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff820f8e39-ffffffff820f8e4d: refcount_dec_and_lock_irqsave.cold (STB_LOCAL)
ffffffff8181ac20-ffffffff8181acbd: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:172
Inline: False
Direct callers:
  - kernel/user.c:free_uid
```
**Symbols:**

```
ffffffff821d695a-ffffffff821d696e: refcount_dec_and_lock_irqsave.cold (STB_LOCAL)
ffffffff8185ffa0-ffffffff8186003d: refcount_dec_and_lock_irqsave (STB_GLOBAL)
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
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637998)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffff800010637998-ffff800010637a60: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd8b0)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
c07dd8b0-c07dd910: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dde40)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
c0000000007dde40-c0000000007ddf24: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464d9a)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffe000464d9a-ffffffe000464e00: refcount_dec_and_lock_irqsave (STB_GLOBAL)
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
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81524620)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff81524620-ffffffff81524689: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514900)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff81514900-ffffffff81514969: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815206b0)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff815206b0-ffffffff81520719: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t *r, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8153a030)
Location: lib/refcount.c:373
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - mm/backing-dev.c:wb_congested_put
```
**Symbols:**

```
ffffffff8153a030-ffffffff8153a099: refcount_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
