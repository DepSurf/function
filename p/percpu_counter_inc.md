# Function: <code>percpu_counter_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a92d3)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In fs/file_table.c (ffffffff8120e0ff)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff8127158f)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/ialloc.c (ffffffff81294098)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/extents_status.c (ffffffff812daf41)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In net/core/sock.c (ffffffff81703ffd)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762daf)
Location: include/linux/percpu_counter.h:175
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817648cd)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8176593b)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_close
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81234b2f)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff8129e332)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/ialloc.c (ffffffff812c2b48)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/extents_status.c (ffffffff8130a8cd)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In net/core/sock.c (ffffffff8176aa5c)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf07f)
Location: include/linux/percpu_counter.h:175
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1015)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff817d6dde)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812476df)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812b3c92)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/ialloc.c (ffffffff812d8140)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/extents_status.c (ffffffff813208cd)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In net/core/sock.c (ffffffff81797b89)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fee8f)
Location: include/linux/percpu_counter.h:175
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800ed5)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81806dfe)
Location: include/linux/percpu_counter.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dcd85)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In fs/file_table.c (ffffffff81252ee8)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812c0e3f)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff812ef855)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f6372)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff817b577d)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f12f)
Location: include/linux/percpu_counter.h:176
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c35)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818274e3)
Location: include/linux/percpu_counter.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81274fe8)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812e4bac)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff81314355)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8131aa7d)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff8182dc29)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e09f)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fc2c)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818a62ef)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8129b8a8)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff813122c6)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff8134221d)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813488f7)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff81878000)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2a65)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c88)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff818fb35c)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0b93)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81328e46)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff81359b1d)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81360aa7)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff818984e2)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff819204d5)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192218a)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819292a0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd501)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff813509bb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff81382b5f)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81389c5d)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff818e2a8f)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982e09)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985270)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8198c1cb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812def21)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81368d3b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff8139c8db)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813a2626)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff81914c6a)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9669)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb360)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819c2b1b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81315aa1)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/quota/dquot.c (ffffffff813b1056)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/extents_status.c (ffffffff813e801b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813ee640)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff819e71db)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa41b9)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6255)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aae0f4)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81bab4cd)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81baef2e)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81320fd1)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/quota/dquot.c (ffffffff813c2656)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff813eb11a)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff813fa31c)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81400d0b)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff819e6a1f)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae7f9)
Location: include/linux/percpu_counter.h:181
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab08a5)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81ab8377)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/mptcp/protocol.c (ffffffff81bbdbca)
Location: include/linux/percpu_counter.h:181
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac7)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813273c0)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/quota/dquot.c (ffffffff813c91ac)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff813f164a)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff814006dc)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff814071fc)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99979)
Location: include/linux/percpu_counter.h:181
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba85)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aa3671)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/mptcp/subflow.c (ffffffff81bb2410)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374690)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff813d01a3)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/quota/dquot.c (ffffffff81419a19)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff8144366d)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff81452cec)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81459ac6)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9983)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f3a9d)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff814588de)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/quota/dquot.c (ffffffff81490485)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff814bf4c8)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff814d01a2)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff814d7796)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff81543643)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134fe2c)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bb226)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff813d8ab2)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813fd37d)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff81439c3c)
Location: include/linux/percpu_counter.h:212
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146bdfa)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff8147c8bd)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff814e740e)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/quota/dquot.c (ffffffff81524005)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff81557428)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff81568af2)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81570501)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2583)
Location: include/linux/percpu_counter.h:212
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380fe5)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813efd25)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8140d1ba)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8143065a)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff8146e8d8)
Location: include/linux/percpu_counter.h:208
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0bcb)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff814b151e)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff8151f230)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/quota/dquot.c (ffffffff8155c40e)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff8158f2a8)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff815a0752)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff815a83b1)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff81619ef3)
Location: include/linux/percpu_counter.h:208
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aa3be)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81420293)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81439932)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8146900e)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff8149d342)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/userfaultfd.c (ffffffff814d03d1)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff814e2cee)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff81553840)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/quota/dquot.c (ffffffff81592bce)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff815c7fb8)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/extents_status.c (ffffffff815d945f)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff815e116e)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff81652e53)
Location: include/linux/percpu_counter.h:265
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
</details>
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
In fs/file_table.c (ffff800010385388)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffff80001043024c)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffff80001046f830)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffff800010475c40)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffff800010bad950)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6ada8)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c960)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffff800010c75928)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e4b4)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (c05f8e8c)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (c0630dc4)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (c0637538)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (c0ccb518)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (c0d79e8c)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7be58)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c0d83fb0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047b76c)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (c000000000541ed4)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (c00000000058fcb0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (c0000000005979b0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (c000000000c83250)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (c000000000d70130)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c48)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c000000000d7d0dc)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe0002583d8)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffe0002cd28a)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffe0002fc300)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffe00030164e)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffe00073fb2c)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0abe)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d22a4)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffe0007d8ab4)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d7501)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8136131b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff81394ebb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8139ac06)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff818b4c6a)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff819594d9)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b1d0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8196298b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c8181)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81351fbb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff8138594b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8138b696)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff8186ebba)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912fc9)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914cc0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8191c47b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d5311)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8135edeb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff8139281b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81398466)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff81905c6a)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3ca9)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c59a0)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819cd15b)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e6161)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81371815)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/ext4/extents_status.c (ffffffff813a6781)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813ac850)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/core/sock.c (ffffffff81926c9f)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd6f9)
Location: include/linux/percpu_counter.h:177
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf480)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819d6ceb)
Location: include/linux/percpu_counter.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
</details>
</li>
</ul>

## Differences
