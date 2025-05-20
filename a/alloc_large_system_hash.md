# Function: <code>alloc_large_system_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f8716b)
Location: mm/page_alloc.c:6312
Inline: False
Direct callers:
  - kernel/pid.c:pidhash_init
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/dcache.c:vfs_caches_init
  - fs/inode.c:inode_init
  - fs/inode.c:inode_init_early
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff81f8716b-ffffffff81f8738c: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81fb1170)
Location: mm/page_alloc.c:6938
Inline: False
Direct callers:
  - kernel/pid.c:pidhash_init
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff81fb1170-ffffffff81fb138c: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81feda3e)
Location: mm/page_alloc.c:6989
Inline: False
Direct callers:
  - kernel/pid.c:pidhash_init
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff81feda3e-ffffffff81fedc5a: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820cf674)
Location: mm/page_alloc.c:7299
Inline: False
Direct callers:
  - kernel/pid.c:pidhash_init
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff820cf674-ffffffff820cf8b2: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff826d8099)
Location: mm/page_alloc.c:7315
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff826d8099-ffffffff826d82eb: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8270253e)
Location: mm/page_alloc.c:7497
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff8270253e-ffffffff82702797: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b9c64)
Location: mm/page_alloc.c:7816
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828b9c64-ffffffff828b9ec0: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d6d9e)
Location: mm/page_alloc.c:8022
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828d6d9e-ffffffff828d702f: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828df223)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828df223-ffffffff828df4a0: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfc5ce)
Location: mm/page_alloc.c:8075
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff82cfc5ce-ffffffff82cfc82b: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe8fe9)
Location: mm/page_alloc.c:8212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff82fe8fe9-ffffffff82fe924f: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f3823)
Location: mm/page_alloc.c:8419
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff831f3823-ffffffff831f3a81: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d9a64)
Location: mm/page_alloc.c:8684
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff832d9a64-ffffffff832d9daf: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348ea3d)
Location: mm/page_alloc.c:8871
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex/core.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff8348ea3d-ffffffff8348edb9: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ec0d00)
Location: mm/page_alloc.c:9045
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex/core.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - lib/stackdepot.c:stack_depot_early_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff83ec0d00-ffffffff83ec1117: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e29a0)
Location: mm/mm_init.c:2450
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex/core.c:futex_init
  - kernel/futex/core.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - lib/stackdepot.c:stack_depot_early_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff836e29a0-ffffffff836e2dae: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff839152a0)
Location: mm/mm_init.c:2446
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex/core.c:futex_init
  - kernel/futex/core.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - lib/stackdepot.c:stack_depot_early_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
  - net/mptcp/token.c:mptcp_token_init
```
**Symbols:**

```
ffffffff839152a0-ffffffff8391563f: alloc_large_system_hash (STB_GLOBAL)
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
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800011458020)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffff800011458020-ffff800011458374: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c1531f8c)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
c1531f8c-c15322dc: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000013817d8)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
c0000000013817d8-c000000001381b10: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0000168fa)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffe0000168fa-ffffffe000016b52: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c80d7)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828c80d7-ffffffff828c8354: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c07fc)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828c07fc-ffffffff828c0a79: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828dae57)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828dae57-ffffffff828db0d4: alloc_large_system_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *alloc_large_system_hash(const char *tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int *_hash_shift, unsigned int *_hash_mask, long unsigned int low_limit, long unsigned int high_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828e0278)
Location: mm/page_alloc.c:8052
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
  - kernel/futex.c:futex_init
  - fs/dcache.c:vfs_caches_init
  - fs/dcache.c:vfs_caches_init_early
  - fs/inode.c:inode_init_early
  - fs/inode.c:inode_init
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_table_init
```
**Symbols:**

```
ffffffff828e0278-ffffffff828e04f5: alloc_large_system_hash (STB_GLOBAL)
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
