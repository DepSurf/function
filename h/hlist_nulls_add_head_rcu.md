# Function: <code>hlist_nulls_add_head_rcu</code>

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
In net/ipv4/inet_hashtables.c (ffffffff817622af)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817633c3)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/udp.c (ffffffff81785ecd)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802475)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff817cef40)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf883)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873739)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff817fed5b)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff673)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7dab)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff8119bd25)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f07c)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f8a3)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce63b)
Location: include/linux/rculist_nulls.h:90
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811ab580)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e01f)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e813)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819534fe)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811c2e0b)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f29cb)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f341a)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf36)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811d44bc)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192043b)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f3a)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e38f1)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811e8db2)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982d62)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983909)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52625)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811f5512)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9751)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba0f5)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8922d)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff81217c89)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In fs/io-wq.c (ffffffff8138a861)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa429f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b8c)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84365)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff8121b52c)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In fs/io-wq.c (ffffffff8139b5a6)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae8df)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf1ec)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93bc4)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bc5f9e)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff8121e5c3)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In fs/io-wq.c (ffffffff813a281f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99a64)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a4ff)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82cd4)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bb6afe)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff812559d3)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In fs/io-wq.c (ffffffff813f122f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - fs/io-wq.c:io_init_new_worker
  - fs/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54ed4)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5596f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4eda4)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81c85b2e)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff8129d730)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In io_uring/io-wq.c (ffffffff816d961f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2c9f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce336d)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81d15963)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/ping.c (ffffffff81d439e4)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def6a5)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81e2bdbe)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff812fa704)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In io_uring/io-wq.c (ffffffff817a54cf)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wqe_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4198)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d9b)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81edc973)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/ping.c (ffffffff81f0ca24)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3775)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82003fce)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff81328da1)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In mm/vmscan.c (ffffffff813b7c24)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In io_uring/io-wq.c (ffffffff817e649f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wq_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f029f7)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0442b)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820245b5)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82080184)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffffffff8134dbc6)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In mm/vmscan.c (ffffffff813e0b11)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In io_uring/io-wq.c (ffffffff8182c25f)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_init_new_worker
  - io_uring/io-wq.c:io_wq_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6cd7)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8751)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f38c5)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82155674)
Location: include/linux/rculist_nulls.h:99
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
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
In kernel/bpf/hashtab.c (ffff800010279940)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6aeb0)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bafc)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55ffc)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (c04abc7c)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (c0d79f80)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a818)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (c0e565ec)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (c0000000003228e8)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (c000000000d70268)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70e04)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f0b0)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffe0001b191e)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0b9c)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d151e)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8b8)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811edb32)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff819595c1)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f65)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a288bd)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811e08c2)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff819130b1)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a55)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e567d)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811eb902)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a079e)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_hash_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_hash_insert
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3d91)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4735)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9446d)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In kernel/bpf/hashtab.c (ffffffff811f9d02)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd7e9)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdff3)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05b2)
Location: include/linux/rculist_nulls.h:91
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
