# Function: <code>__cmpxchg_u64_relaxed</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001832a8)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_q_add_safe
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/locking/mutex.c (c000000000ee5248)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
```
```
In kernel/locking/rtmutex.c (c000000000ee7e64)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
```
In kernel/futex.c (c00000000021d39c)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In fs/crypto/hooks.c (c000000000519784)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/crypto/keysetup.c (c00000000051c988)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In lib/lockref.c (c0000000007caf18)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
```
```
In lib/refcount.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
```
```
In lib/generic-radix-tree.c (c0000000007de8cc)
Location: arch/powerpc/include/asm/cmpxchg.h:362
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
```
</details>
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
