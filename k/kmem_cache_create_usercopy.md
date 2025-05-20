# Function: <code>kmem_cache_create_usercopy</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:436
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff8121f23b-ffffffff8121f275: kmem_cache_create_usercopy.cold.30 (STB_LOCAL)
ffffffff8121e840-ffffffff8121ea64: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:438
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff8123226f-ffffffff812322a9: kmem_cache_create_usercopy.cold.31 (STB_LOCAL)
ffffffff81231820-ffffffff81231a44: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:453
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81242784-ffffffff812427f1: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff81241c70-ffffffff81241e8d: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81250c79-ffffffff81250cb2: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff812500f0-ffffffff81250311: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff8127f2e6-ffffffff8127f31f: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff8127e730-ffffffff8127e951: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:302
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81be72bb-ffffffff81be72f6: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff81287c20-ffffffff81287ebd: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:310
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81bd905c-ffffffff81bd9098: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff8128cef0-ffffffff8128d17b: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:310
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81cbb384-ffffffff81cbb3ce: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff812ccd10-ffffffff812ccf9b: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:302
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81e6cd3a-ffffffff81e6cd81: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff8132b500-ffffffff8132b7f9: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0980)
Location: mm/slab_common.c:278
Inline: False
Direct callers:
  - kernel/fork.c:mm_cache_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff813a0980-ffffffff813a0c9c: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3c40)
Location: mm/slab_common.c:278
Inline: False
Direct callers:
  - kernel/fork.c:mm_cache_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff813d3c40-ffffffff813d3f1a: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe8e0)
Location: mm/slab_common.c:273
Inline: False
Direct callers:
  - kernel/fork.c:mm_cache_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - io_uring/io_uring.c:io_uring_init
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff813fe8e0-ffffffff813febba: kmem_cache_create_usercopy (STB_GLOBAL)
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
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e7038)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffff8000102e7038-ffff8000102e7284: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050b20c)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
c050b20c-c050b448: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a8b90)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/fork.c:thread_stack_cache_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
c0000000003a8b90-c0000000003a8ec8: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fcd0c)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffe0001fcd0c-ffffffe0001fcedc: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff812492c9-ffffffff81249302: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff81248740-ffffffff81248961: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff8123c279-ffffffff8123c2b2: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff8123b6f0-ffffffff8123b911: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81247069-ffffffff812470a2: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff812464e0-ffffffff81246701: kmem_cache_create_usercopy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *kmem_cache_create_usercopy(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:454
Inline: False
Direct callers:
  - kernel/fork.c:proc_caches_init
  - kernel/fork.c:fork_init
  - kernel/utsname.c:uts_ns_init
  - mm/slab_common.c:kmem_cache_create
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init
  - fs/verity/open.c:fsverity_init_info_cache
  - fs/proc/inode.c:proc_init_kmemcache
  - fs/ext4/super.c:ext4_init_fs
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
  - net/core/sock.c:proto_register
  - net/core/skbuff.c:skb_init
```
**Symbols:**

```
ffffffff81256899-ffffffff812568d2: kmem_cache_create_usercopy.cold (STB_LOCAL)
ffffffff81255cf0-ffffffff81255f11: kmem_cache_create_usercopy (STB_GLOBAL)
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
