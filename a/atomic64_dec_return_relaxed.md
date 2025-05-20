# Function: <code>atomic64_dec_return_relaxed</code>

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
In kernel/acct.c (c0000000002301a8)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
```
```
In kernel/audit_tree.c (c00000000026ab08)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/events/core.c (c00000000034c900)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
```
```
In fs/file_table.c (c00000000047bb58)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
```
```
In fs/notify/mark.c (c0000000004f0218)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In block/blk-ioc.c (c00000000077d4b8)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
```
```
In net/unix/scm.c (c000000000e1b61c)
Location: arch/powerpc/include/asm/atomic.h:443
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
