# Function: <code>is_a_nulls</code>

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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:37
Inline: True
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:42
Inline: True
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/list_nulls.h:43
Inline: True
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
In kernel/bpf/hashtab.c (ffffffff811c1b7b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f23d0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3720)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4de5)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eed5)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff8193af2b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ace3b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811d309b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fdd0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81921240)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81923015)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d305)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff8196ac1b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e37f8)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811e7d7e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819826dc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c00)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819859b7)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1735)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff819d18e1)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52523)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811f44de)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8f5c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba3e0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe57)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d83e5)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff81a08444)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89133)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff812186ce)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In fs/io-wq.c (ffffffff8138a2c6)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3a12)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f7c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6912)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4398)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/ping.c (ffffffff81af7a1e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84263)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff81219ece)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In fs/io-wq.c (ffffffff8139b1fc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae052)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_lookup_by_sk
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf5e7)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f62)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0d56)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81b048fe)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93ac9)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bc6124)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff8121db8e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In fs/io-wq.c (ffffffff813a282d)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99132)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8ef)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c34d)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbe22)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff81af016e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82bd9)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bb6c84)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff812549ee)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In fs/io-wq.c (ffffffff813f123c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - fs/io-wq.c:io_init_new_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b545af)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d5f)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57c0d)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7ba65)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/ping.c (ffffffff81bb017e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4eca9)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81c85cb4)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff8129d0fe)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In io_uring/io-wq.c (ffffffff816d962c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce263a)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a87)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b9e)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ab88)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81d15aed)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/ping.c (ffffffff81d42aee)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/raw.c (ffffffff81dbe383)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def65e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81e2bf98)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff812f8fee)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In io_uring/io-wq.c (ffffffff817a54dc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea36bb)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea63d1)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8db7)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0460)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81edbebd)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/ping.c (ffffffff81f0b9be)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/raw.c (ffffffff81f8e8e3)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc372e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff820041d8)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff81327ace)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In mm/vmscan.c (ffffffff813b7f49)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In io_uring/io-wq.c (ffffffff817e64b7)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01f1b)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04bb1)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07637)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f110)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202456e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff820803d0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffffffff8134c18e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:bpf_for_each_hash_elem
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_find_next
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In mm/vmscan.c (ffffffff813e0ea9)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In io_uring/io-wq.c (ffffffff8182c277)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc8299)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8eba)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb997)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4660)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f387e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff821558c0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_exists
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:__token_bucket_busy
  - net/mptcp/token.c:__token_bucket_busy
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
In kernel/bpf/hashtab.c (ffff80001027800c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a81c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bf5c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d31c)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ba44)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffff800010cc166c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55f30)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (c04aa768)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (c0d79954)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7ade0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c2dc)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9a100)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/ping.c (c0dcb3bc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (c0e564c0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (c0000000003211e4)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (c000000000d6fa2c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d715f4)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d732b8)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98374)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/ping.c (c000000000dda89c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8efc0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffe0001b023e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0364)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1994)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fce)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb57a)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/ping.c (ffffffe00081568a)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_get_first
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d7ca)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811ecafe)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958dcc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a250)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bcc7)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978255)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff819a81e4)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a287c3)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811df88e)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819128bc)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913d40)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819157b7)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931d15)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff81961ca4)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5583)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811ea8ce)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a0770)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_hash_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_hash_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
  - net/netfilter/nf_conntrack_core.c:nf_ct_add_to_dying_list
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a10e1)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_next
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a916f)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0ca0)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c359c)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a20)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6497)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2a25)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff81a12a84)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94373)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In kernel/bpf/hashtab.c (ffffffff811f8cae)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:lookup_nulls_elem_raw
  - kernel/bpf/hashtab.c:lookup_elem_raw
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd26d)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4a9)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cffb8)
Location: include/linux/list_nulls.h:43
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec895)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/ping.c (ffffffff81a1d454)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa04c8)
Location: include/linux/list_nulls.h:43
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
</li>
</ul>

## Differences
