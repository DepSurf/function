# Function: <code>refcount_dec_and_lock</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8146c530)
Location: lib/refcount.c:337
Inline: True
```
**Symbols:**

```
ffffffff8146c530-ffffffff8146c570: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81498840)
Location: lib/refcount.c:338
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81498840-ffffffff81498886: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814cda30)
Location: lib/refcount.c:338
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff814cda30-ffffffff814cda71: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e2300)
Location: lib/refcount.c:337
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keyinfo.c:put_crypt_info
```
**Symbols:**

```
ffffffff814e2300-ffffffff814e2341: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e190)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keyinfo.c:put_crypt_info
```
**Symbols:**

```
ffffffff8150e190-ffffffff8150e1e2: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152bfe0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff8152bfe0-ffffffff8152c032: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8158f9e0)
Location: lib/refcount.c:144
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff8158f9e0-ffffffff8158fa64: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815ac510)
Location: lib/refcount.c:144
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
```
**Symbols:**

```
ffffffff815ac510-ffffffff815ac594: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815b71e0)
Location: lib/refcount.c:144
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff815b71e0-ffffffff815b7264: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/refcount.c (ffffffff8161d83b)
Location: lib/refcount.c:144
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_put
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff81cdae0a-ffffffff81cdae1e: refcount_dec_and_lock.cold (STB_LOCAL)
ffffffff8161d810-ffffffff8161d8a0: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:144
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff81e936b2-ffffffff81e936c6: refcount_dec_and_lock.cold (STB_LOCAL)
ffffffff816eb270-ffffffff816eb2f8: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:144
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff8207887a-ffffffff8207888e: refcount_dec_and_lock.cold (STB_LOCAL)
ffffffff817db910-ffffffff817db998: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:144
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff820f8e25-ffffffff820f8e39: refcount_dec_and_lock.cold (STB_LOCAL)
ffffffff8181ab80-ffffffff8181ac08: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/refcount.c (0)
Location: lib/refcount.c:144
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/landlock/object.c:landlock_put_object
```
**Symbols:**

```
ffffffff821d6946-ffffffff821d695a: refcount_dec_and_lock.cold (STB_LOCAL)
ffffffff8185ff00-ffffffff8185ff88: refcount_dec_and_lock (STB_GLOBAL)
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
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637cb0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffff800010637cb0-ffff800010637d4c: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd850)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
c07dd850-c07dd8b0: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007ddd20)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
c0000000007ddd20-c0000000007dde3c: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464cf0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffe000464cf0-ffffffe000464d9a: refcount_dec_and_lock (STB_GLOBAL)
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
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815245c0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff815245c0-ffffffff81524612: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815148a0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff815148a0-ffffffff815148f2: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520650)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81520650-ffffffff815206a2: refcount_dec_and_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool refcount_dec_and_lock(refcount_t *r, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539fd0)
Location: lib/refcount.c:345
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81539fd0-ffffffff8153a028: refcount_dec_and_lock (STB_GLOBAL)
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
