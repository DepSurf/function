# Function: <code>inet_ehash_lockp</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81762026)
Location: include/net/inet_hashtables.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763338)
Location: include/net/inet_hashtables.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/inet_hashtables.h:159
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/inet_hashtables.h:159
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/inet_hashtables.h:159
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
In net/ipv4/inet_hashtables.c (ffffffff817ce4c9)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf7f8)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d174c)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e7c71)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873627)
Location: include/net/inet_hashtables.h:155
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
In net/ipv4/inet_hashtables.c (ffffffff817fe2d9)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff5e8)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818015fc)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181842e)
Location: include/net/inet_hashtables.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7c97)
Location: include/net/inet_hashtables.h:155
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
In net/ipv4/inet_hashtables.c (ffffffff8181e6ae)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f818)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182151f)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818388fe)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce51c)
Location: include/net/inet_hashtables.h:163
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
In net/ipv4/inet_hashtables.c (ffffffff8189d5ce)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e788)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a08df)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b804e)
Location: include/net/inet_hashtables.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819533ec)
Location: include/net/inet_hashtables.h:163
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
In net/ipv4/inet_hashtables.c (ffffffff818f22d2)
Location: include/net/inet_hashtables.h:176
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f339f)
Location: include/net/inet_hashtables.h:176
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4dbf)
Location: include/net/inet_hashtables.h:176
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910ede)
Location: include/net/inet_hashtables.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ace1b)
Location: include/net/inet_hashtables.h:176
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
In net/ipv4/inet_hashtables.c (ffffffff8191fcd2)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920ebf)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922fef)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f3ae)
Location: include/net/inet_hashtables.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e37e0)
Location: include/net/inet_hashtables.h:177
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
In net/ipv4/inet_hashtables.c (ffffffff819825e5)
Location: include/net/inet_hashtables.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8198388f)
Location: include/net/inet_hashtables.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198598f)
Location: include/net/inet_hashtables.h:173
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2fde)
Location: include/net/inet_hashtables.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52500)
Location: include/net/inet_hashtables.h:173
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
In net/ipv4/inet_hashtables.c (ffffffff819b8e65)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba07f)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe2f)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d9bde)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89110)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff81aa3925)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b0f)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa68b7)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6e3e)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84240)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff81aadf65)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf16f)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f07)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad310c)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93aab)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81a99045)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a482)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c27c)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe19c)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82bbb)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81b544c5)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b558f2)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57b3c)
Location: include/net/inet_hashtables.h:185
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bac9)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ec8b)
Location: include/net/inet_hashtables.h:185
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ce255d)
Location: include/net/inet_hashtables.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce32f2)
Location: include/net/inet_hashtables.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b38)
Location: include/net/inet_hashtables.h:157
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ad16)
Location: include/net/inet_hashtables.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def648)
Location: include/net/inet_hashtables.h:157
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea35ce)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b68)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d51)
Location: include/net/inet_hashtables.h:205
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed05f0)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3718)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f01e18)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f042e6)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f075d1)
Location: include/net/inet_hashtables.h:205
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f2a6)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024558)
Location: include/net/inet_hashtables.h:205
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc80c8)
Location: include/net/inet_hashtables.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8636)
Location: include/net/inet_hashtables.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb931)
Location: include/net/inet_hashtables.h:200
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff47f6)
Location: include/net/inet_hashtables.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3868)
Location: include/net/inet_hashtables.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffff800010c6a72c)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6ba7c)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d2d4)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b2fc)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55f04)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (c0d79844)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a7d8)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c2a4)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d98e54)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (c0e564b8)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (c000000000d6f8d0)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70d80)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73284)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9754c)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8efb4)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffe0007d0276)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1486)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fa6)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007edd40)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d78e)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff81958cd5)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959eef)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bc9f)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81979a4e)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a287a0)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff819127c5)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819139df)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8191578f)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193350e)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5560)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff819c34a5)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c46bf)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c646f)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e421e)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94350)
Location: include/net/inet_hashtables.h:179
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
In net/ipv4/inet_hashtables.c (ffffffff819cd175)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdf7f)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cff8c)
Location: include/net/inet_hashtables.h:179
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb0fe)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa04aa)
Location: include/net/inet_hashtables.h:179
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
