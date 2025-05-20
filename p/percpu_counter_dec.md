# Function: <code>percpu_counter_dec</code>

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
In fs/file_table.c (ffffffff8120e1dc)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff812714c4)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/ext4/ialloc.c (ffffffff812941d0)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/extents_status.c (ffffffff812dac26)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8176496f)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cb43)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff81234f93)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff8129fe7a)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/ialloc.c (ffffffff812c264a)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/extents_status.c (ffffffff8130a6c1)
Location: include/linux/percpu_counter.h:180
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0ec2)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea46d)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff81247b40)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812b5369)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/ialloc.c (ffffffff812d7c7f)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/extents_status.c (ffffffff813206c1)
Location: include/linux/percpu_counter.h:180
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800d82)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818c65)
Location: include/linux/percpu_counter.h:180
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff81253370)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812c1b2a)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff812ef681)
Location: include/linux/percpu_counter.h:181
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812f5f40)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820b3f)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839438)
Location: include/linux/percpu_counter.h:181
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff81275473)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812e5977)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81314181)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8131a596)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fb25)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8b9e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff8129bcf3)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff81312ff0)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81342028)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81348241)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4b91)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e05a)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812b09c1)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81329f80)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81359928)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813603f1)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922091)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c44a)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812cd33f)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81351af7)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81382988)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81389571)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198518e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a088b)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812ded5f)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81369e77)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff8139ae88)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813a1ea6)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb23e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d744c)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff81315ebf)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813b1216)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff813e6378)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff813edfac)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6126)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5ec8)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/mptcp/protocol.c (ffffffff81bab54b)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
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
In fs/file_table.c (ffffffff81321449)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/io_uring.c (ffffffff81390295)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/io_uring.c:__io_free_req
```
```
In fs/quota/dquot.c (ffffffff813c280c)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff813f86a8)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff814005fd)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0776)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1af8)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/mptcp/protocol.c (ffffffff81bc0a03)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
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
In fs/file_table.c (ffffffff813271e9)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813c93e3)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff813ff1e8)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff81406aaa)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b956)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
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
In fs/file_table.c (ffffffff81374a8d)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/eventpoll.c (ffffffff813d05bd)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/quota/dquot.c (ffffffff81419c66)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff814517f8)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff8145932e)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9b31)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
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
In fs/file_table.c (ffffffff813f388b)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/eventpoll.c (ffffffff81458d19)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/quota/dquot.c (ffffffff814906d1)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff814cdd6e)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff814d6d1e)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff8154385c)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
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
In kernel/events/uprobes.c (ffffffff8134fe05)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bc00e)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff813d9bea)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813fd2cd)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8141f24a)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In fs/file_table.c (ffffffff8147c678)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/eventpoll.c (ffffffff814e7849)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/quota/dquot.c (ffffffff81524251)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff815664fe)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff8156faa3)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff815e27bc)
Location: include/linux/percpu_counter.h:217
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
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
In kernel/events/uprobes.c (ffffffff81380fbe)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813f0a33)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8140e2dd)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81430579)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81453d1c)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In fs/file_table.c (ffffffff814b11d2)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/eventpoll.c (ffffffff8151f6b5)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
```
```
In fs/quota/dquot.c (ffffffff8155c652)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff8159e18e)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff815a7926)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a122)
Location: include/linux/percpu_counter.h:213
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
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
In kernel/events/uprobes.c (ffffffff813aa397)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff814202c6)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8143ab00)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81468f1c)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8148e6bb)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In fs/file_table.c (ffffffff814e2998)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/eventpoll.c (ffffffff81553cc5)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
```
```
In fs/quota/dquot.c (ffffffff81592e1f)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/ext4/extents_status.c (ffffffff815d6d1e)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff815e0757)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/jbd2/checkpoint.c (ffffffff81653065)
Location: include/linux/percpu_counter.h:270
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
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
In fs/file_table.c (ffff800010385544)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffff800010431fa8)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffff80001046d918)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffff800010475660)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c800)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c260)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (c056e304)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (c05fa1b8)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (c062ed64)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (c0636dac)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (c0d7bd00)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (c0d99dc4)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (c00000000047b4d0)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (c000000000543228)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (c00000000058d8a0)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (c000000000597180)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72ab4)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97ef0)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffe000258218)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffe0002ce384)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffe0002fab94)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffe00030105c)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2112)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb3da)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812d733f)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81362457)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81393468)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8139a486)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b0ae)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819772bc)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812c7fbf)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813530f7)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81383ef8)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8138af16)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914b9e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930d7c)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812d514f)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff8135ff27)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff81390dc8)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81397ce6)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c587e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1a8c)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In fs/file_table.c (ffffffff812e5fa4)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813729e3)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/ext4/extents_status.c (ffffffff813a4c5e)
Location: include/linux/percpu_counter.h:182
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813abac6)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf35e)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb7bc)
Location: include/linux/percpu_counter.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
</details>
</li>
</ul>

## Differences
