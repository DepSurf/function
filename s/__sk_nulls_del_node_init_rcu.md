# Function: <code>__sk_nulls_del_node_init_rcu</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81762043)
Location: include/net/sock.h:612
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817633e3)
Location: include/net/sock.h:612
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817651e6)
Location: include/net/sock.h:612
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8178684b)
Location: include/net/sock.h:612
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8180249a)
Location: include/net/sock.h:612
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
In net/ipv4/inet_hashtables.c (ffffffff817ce4f7)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf8a3)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1766)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187375e)
Location: include/net/sock.h:605
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
In net/ipv4/inet_hashtables.c (ffffffff817fe307)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff693)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801616)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7dd0)
Location: include/net/sock.h:626
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
In net/ipv4/inet_hashtables.c (ffffffff8181e6dc)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f8c1)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821515)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce659)
Location: include/net/sock.h:640
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
In net/ipv4/inet_hashtables.c (ffffffff8189d5f8)
Location: include/net/sock.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e82d)
Location: include/net/sock.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a08d5)
Location: include/net/sock.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953520)
Location: include/net/sock.h:644
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
In net/ipv4/inet_hashtables.c (ffffffff818f23c0)
Location: include/net/sock.h:651
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f342d)
Location: include/net/sock.h:651
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4dd5)
Location: include/net/sock.h:651
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf4e)
Location: include/net/sock.h:651
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
In net/ipv4/inet_hashtables.c (ffffffff8191fdc0)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f4d)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81923005)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3909)
Location: include/net/sock.h:671
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
In net/ipv4/inet_hashtables.c (ffffffff819826cc)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8198391c)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819859a5)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a5263f)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff819b8f0f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba10f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe45)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8924f)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff81aa39d6)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b9f)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa68cd)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8437f)
Location: include/net/sock.h:715
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
In net/ipv4/inet_hashtables.c (ffffffff81aae016)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf1ff)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f1d)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93bde)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bc6142)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81a990f6)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a512)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c295)
Location: include/net/sock.h:722
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82cee)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81bb6ca2)
Location: include/net/sock.h:722
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81b54573)
Location: include/net/sock.h:734
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55982)
Location: include/net/sock.h:734
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57b55)
Location: include/net/sock.h:734
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4edbe)
Location: include/net/sock.h:734
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81c85cd2)
Location: include/net/sock.h:734
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81ce25f7)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3380)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b4e)
Location: include/net/sock.h:773
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d159e2)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def6bf)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff81e2bfb6)
Location: include/net/sock.h:773
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3678)
Location: include/net/sock.h:799
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5cd5)
Location: include/net/sock.h:799
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d67)
Location: include/net/sock.h:799
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edbd92)
Location: include/net/sock.h:799
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc378f)
Location: include/net/sock.h:799
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff820041f6)
Location: include/net/sock.h:799
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81f01ecf)
Location: include/net/sock.h:801
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0443f)
Location: include/net/sock.h:801
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f075e7)
Location: include/net/sock.h:801
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820245cf)
Location: include/net/sock.h:801
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff820803ee)
Location: include/net/sock.h:801
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffffffff81fc8108)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8765)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb947)
Location: include/net/sock.h:784
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f38df)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/mptcp/token.c (ffffffff821558de)
Location: include/net/sock.h:784
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In net/ipv4/inet_hashtables.c (ffff800010c6a80c)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bb18)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d30c)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d5601c)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (c0d79904)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a83c)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c2bc)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c0e56618)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (c000000000d6f9b0)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70e28)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d732a0)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f0dc)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffe0007d0322)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d153c)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fa8)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8e2)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff81958d7f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f7f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bcb5)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a288df)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff8191286f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a6f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819157a5)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e569f)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff819c354f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c474f)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6485)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9448f)
Location: include/net/sock.h:673
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
In net/ipv4/inet_hashtables.c (ffffffff819cd220)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce00d)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cffa2)
Location: include/net/sock.h:673
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05d5)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
</li>
</ul>

## Differences
