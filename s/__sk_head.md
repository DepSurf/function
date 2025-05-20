# Function: <code>__sk_head</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81763041)
Location: include/net/sock.h:510
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:510
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:510
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/net/sock.h:510
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
In net/ipv4/inet_hashtables.c (ffffffff817cf414)
Location: include/net/sock.h:503
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e921d)
Location: include/net/sock.h:503
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f17ef)
Location: include/net/sock.h:503
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:503
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854d92)
Location: include/net/sock.h:503
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff817ff204)
Location: include/net/sock.h:524
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181941f)
Location: include/net/sock.h:524
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8182256c)
Location: include/net/sock.h:524
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:524
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81886b02)
Location: include/net/sock.h:524
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff8181f46c)
Location: include/net/sock.h:539
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183a5e9)
Location: include/net/sock.h:539
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818431d7)
Location: include/net/sock.h:539
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:539
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818ad02e)
Location: include/net/sock.h:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff8189e3cc)
Location: include/net/sock.h:543
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba0e9)
Location: include/net/sock.h:543
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c2b97)
Location: include/net/sock.h:543
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:543
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192fc3e)
Location: include/net/sock.h:543
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff818f2e44)
Location: include/net/sock.h:550
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910b90)
Location: include/net/sock.h:550
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81918dd8)
Location: include/net/sock.h:550
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81958c4e)
Location: include/net/sock.h:550
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819888de)
Location: include/net/sock.h:550
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81920b74)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e880)
Location: include/net/sock.h:570
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81947628)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8198d7fe)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819bf24e)
Location: include/net/sock.h:570
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81983455)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2cb4)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abcb8)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff819f8efd)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a2de8e)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff819b9ccb)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819e2968)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a2fb4d)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a649fe)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81aa44e7)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81acff5b)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/unix/af_unix.c (ffffffff81b23bd9)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b5d34a)
Location: include/net/sock.h:614
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81aaeb37)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81adbedb)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/unix/af_unix.c (ffffffff81b325a9)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b6bb3a)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81a99d77)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81ac6d7c)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/unix/af_unix.c (ffffffff81b200d2)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b59e5a)
Location: include/net/sock.h:621
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81b551e7)
Location: include/net/sock.h:633
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81b8559c)
Location: include/net/sock.h:633
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/unix/af_unix.c (ffffffff81be4f6f)
Location: include/net/sock.h:633
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81c214ca)
Location: include/net/sock.h:633
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81ce2da1)
Location: include/net/sock.h:672
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/unix/af_unix.c (ffffffff81d7cd8a)
Location: include/net/sock.h:672
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f49eb8)
Location: include/net/sock.h:703
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fa9b58)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82076fd8)
Location: include/net/sock.h:688
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_get_first
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
In net/ipv4/inet_hashtables.c (ffff800010c6b560)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffff800010c9688c)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffff800010cef064)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffff800010d2a8e8)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (c0d7a5dc)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (c0da4f1c)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (c0df6a54)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c0e2e864)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (c000000000d70a40)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (c000000000da8338)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (c000000000e14bec)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c000000000e5baa8)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffe0007d1154)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5a9c)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffe00083c11a)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffe00086afb6)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff81959b3b)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819827d8)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff819cf1dd)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a0408e)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff8191362b)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff8193c298)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8198bf9d)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819c0e4e)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff819c430b)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819ecfa8)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a39c5d)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a6eb0e)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv4/inet_hashtables.c (ffffffff819cdd77)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819f6e98)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a4629d)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a7b13e)
Location: include/net/sock.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
</details>
</li>
</ul>

## Differences
