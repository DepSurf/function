# Function: <code>hlist_nulls_del_init_rcu</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81762048)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817633e8)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817651ef)
Location: include/linux/rculist_nulls.h:32
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81785e97)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8180249f)
Location: include/linux/rculist_nulls.h:32
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
In net/ipv4/inet_hashtables.c (ffffffff817ce4fc)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf8a8)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d176f)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873763)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
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
In net/ipv4/inet_hashtables.c (ffffffff817fe30c)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff698)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180161f)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7dd5)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
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
In net/ipv4/inet_hashtables.c (ffffffff8181e6e1)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f8c6)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182153e)
Location: include/linux/rculist_nulls.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce65e)
Location: include/linux/rculist_nulls.h:32
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
In net/ipv4/inet_hashtables.c (ffffffff8189d601)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e836)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a08fe)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953529)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff818f23c9)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3436)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4dde)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf58)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff8191fdc9)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f56)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192300e)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3912)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff819826d5)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983925)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819859af)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52648)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff819b8f55)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba118)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe4f)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89258)
Location: include/linux/rculist_nulls.h:33
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
In fs/io-wq.c (ffffffff8138a419)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3a0b)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4bc7)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa690a)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84428)
Location: include/linux/rculist_nulls.h:33
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
In fs/io-wq.c (ffffffff8139b369)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae04b)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf227)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f5a)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93c87)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bc6163)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In fs/io-wq.c (ffffffff813a2f4f)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9912b)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a53a)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c345)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82d97)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bb6cc3)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In fs/io-wq.c (ffffffff813f24f5)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b545a8)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b559aa)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57c05)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ee67)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81c85cf3)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In io_uring/io-wq.c (ffffffff816dafe2)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2633)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce33b4)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b97)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d15a02)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/ping.c (ffffffff81d42ae7)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def83c)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81e2bff9)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In io_uring/io-wq.c (ffffffff817a70ca)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea36b4)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d1b)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8db0)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edbdb2)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/ping.c (ffffffff81f0b9b7)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc390c)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82004239)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In mm/vmscan.c (ffffffff813b7d6f)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_release_memcg
```
```
In io_uring/io-wq.c (ffffffff817e81f7)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01f14)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04485)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f07630)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024757)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82080437)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In mm/vmscan.c (ffffffff813e0ca2)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_release_memcg
```
```
In io_uring/io-wq.c (ffffffff8182dff6)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc8292)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc87ab)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb990)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a67)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff82155927)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
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
In net/ipv4/inet_hashtables.c (ffff800010c6a814)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bb20)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d314)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d56024)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (c0d79948)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a848)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c2cc)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c0e56624)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (c000000000d6fa20)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70e34)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d732ac)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f0e8)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffe0007d0360)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1542)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fca)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8e8)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff81958dc5)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f88)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bcbf)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a288e8)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff819128b5)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a78)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819157af)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e56a8)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff819c3595)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4758)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c648f)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94498)
Location: include/linux/rculist_nulls.h:33
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
In net/ipv4/inet_hashtables.c (ffffffff819cd266)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce016)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cffb0)
Location: include/linux/rculist_nulls.h:33
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05de)
Location: include/linux/rculist_nulls.h:33
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
