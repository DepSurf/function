# Function: <code>_atomic_dec_and_lock_irqsave</code>

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
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff819ce200)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff819ce200-ffffffff819ce256: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a076c0)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81a076c0-ffffffff81a07716: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a77040)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81a77040-ffffffff81a770a7: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81aae420)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81aae420-ffffffff81aae487: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff815e8140)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - block/keyslot-manager.c:blk_ksm_put_slot
```
**Symbols:**

```
ffffffff815e8140-ffffffff815e81a7: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8160d300)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - block/keyslot-manager.c:blk_ksm_put_slot
```
**Symbols:**

```
ffffffff8160d300-ffffffff8160d367: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff815f0a60)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - block/keyslot-manager.c:blk_ksm_put_slot
```
**Symbols:**

```
ffffffff815f0a60-ffffffff815f0ac7: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8165dba0)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - kernel/ucount.c:put_ucounts
  - block/keyslot-manager.c:blk_ksm_put_slot
```
**Symbols:**

```
ffffffff8165dba0-ffffffff8165dc07: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff817771c0)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - kernel/ucount.c:put_ucounts
  - block/blk-crypto-profile.c:blk_crypto_put_keyslot
```
**Symbols:**

```
ffffffff817771c0-ffffffff81777226: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8201fb60)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - kernel/ucount.c:put_ucounts
  - block/blk-crypto-profile.c:blk_crypto_put_keyslot
```
**Symbols:**

```
ffffffff8201fb60-ffffffff8201fbc6: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff8209fa70)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - kernel/ucount.c:put_ucounts
  - block/blk-crypto-profile.c:blk_crypto_put_keyslot
```
**Symbols:**

```
ffffffff8209fa70-ffffffff8209fad4: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff82177a40)
Location: lib/dec_and_lock.c:37
Inline: False
Direct callers:
  - kernel/ucount.c:put_ucounts
  - block/blk-crypto-profile.c:blk_crypto_put_keyslot
```
**Symbols:**

```
ffffffff82177a40-ffffffff82177aa4: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
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
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffff800010d84800)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffff800010d84800-ffff800010d84954: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (c0e7fc7c)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
c0e7fc7c-c0e7fd24: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (c000000000ec3a00)
Location: lib/dec_and_lock.c:37
Inline: False
```
**Symbols:**

```
c000000000ec3a00-c000000000ec3b0c: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffe0008aec5c)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffe0008aec5c-ffffffe0008aecd4: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
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
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a4d270)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81a4d270-ffffffff81a4d2d7: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81a0a3a0)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81a0a3a0-ffffffff81a0a407: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81ab9660)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81ab9660-ffffffff81ab96c7: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int _atomic_dec_and_lock_irqsave(atomic_t *atomic, spinlock_t *lock, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dec_and_lock.c (ffffffff81ac5ab0)
Location: lib/dec_and_lock.c:37
Inline: True
```
**Symbols:**

```
ffffffff81ac5ab0-ffffffff81ac5b17: _atomic_dec_and_lock_irqsave (STB_GLOBAL)
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
