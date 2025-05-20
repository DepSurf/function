# Function: <code>__cmpxchg_u32_relaxed</code>

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
In kernel/sched/core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In kernel/locking/osq_lock.c (c0000000001c2470)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In kernel/locking/rtmutex.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In fs/crypto/keysetup.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In lib/lockref.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
```
```
In lib/refcount.c (c0000000007dd794)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/generic-radix-tree.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:268
Inline: True
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
