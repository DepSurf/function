# Function: <code>__cmpxchg_case_rel_64</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da2f74)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: False
```
```
In kernel/locking/rtmutex.c (ffff800010da583c)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
```
In fs/crypto/hooks.c (ffff80001040c87c)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/crypto/keysetup.c (ffff80001040f138)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In lib/refcount.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: False
```
```
In lib/generic-radix-tree.c (ffff8000106385e4)
Location: arch/arm64/include/asm/cmpxchg.h:126
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
