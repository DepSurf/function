# Function: <code>sk_head</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81763039)
Location: include/net/sock.h:515
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81784214)
Location: include/net/sock.h:515
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff817be41e)
Location: include/net/sock.h:515
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff817e69f5)
Location: include/net/sock.h:515
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
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf403)
Location: include/net/sock.h:508
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e9211)
Location: include/net/sock.h:508
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f17e7)
Location: include/net/sock.h:508
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8182b3b2)
Location: include/net/sock.h:508
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81854d7d)
Location: include/net/sock.h:508
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ff1f3)
Location: include/net/sock.h:529
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81819413)
Location: include/net/sock.h:529
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81822564)
Location: include/net/sock.h:529
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8185cddf)
Location: include/net/sock.h:529
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81886aed)
Location: include/net/sock.h:529
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f45d)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183a5dd)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818431be)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8188156b)
Location: include/net/sock.h:544
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff818ad01d)
Location: include/net/sock.h:544
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e3bd)
Location: include/net/sock.h:548
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba0dd)
Location: include/net/sock.h:548
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818c2b7e)
Location: include/net/sock.h:548
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8190270b)
Location: include/net/sock.h:548
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff8192fc2d)
Location: include/net/sock.h:548
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2e35)
Location: include/net/sock.h:555
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910b84)
Location: include/net/sock.h:555
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81918dcc)
Location: include/net/sock.h:555
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81958c41)
Location: include/net/sock.h:555
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819888cd)
Location: include/net/sock.h:555
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
In net/ipv4/inet_hashtables.c (ffffffff81920b69)
Location: include/net/sock.h:575
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e874)
Location: include/net/sock.h:575
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8194761c)
Location: include/net/sock.h:575
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8198d7f1)
Location: include/net/sock.h:575
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819bf23d)
Location: include/net/sock.h:575
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
In net/ipv4/inet_hashtables.c (ffffffff8198344a)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2ca4)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819abcac)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff819f8ef0)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a2de7d)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff819b9cc0)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819e295c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a2fb40)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a649ed)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff81aa44de)
Location: include/net/sock.h:619
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81acff4b)
Location: include/net/sock.h:619
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81b23bcc)
Location: include/net/sock.h:619
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b5d339)
Location: include/net/sock.h:619
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
In net/ipv4/inet_hashtables.c (ffffffff81aaeb2e)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81adbecb)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81b3259c)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b6bb29)
Location: include/net/sock.h:626
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
In net/ipv4/inet_hashtables.c (ffffffff81a99d6e)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81ac6d6c)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81b200c5)
Location: include/net/sock.h:626
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81b59e49)
Location: include/net/sock.h:626
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
In net/ipv4/inet_hashtables.c (ffffffff81b551de)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff81b8558c)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81be4f62)
Location: include/net/sock.h:638
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81c214b9)
Location: include/net/sock.h:638
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
In net/ipv4/inet_hashtables.c (ffffffff81ce2d98)
Location: include/net/sock.h:677
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/unix/af_unix.c (ffffffff81d7cd7d)
Location: include/net/sock.h:677
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
In net/unix/af_unix.c (ffffffff81f49eb0)
Location: include/net/sock.h:708
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
In net/unix/af_unix.c (ffffffff81fa9b50)
Location: include/net/sock.h:710
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
In net/unix/af_unix.c (ffffffff82076fd0)
Location: include/net/sock.h:693
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
In net/ipv4/inet_hashtables.c (ffff800010c6b554)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffff800010c96874)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffff800010cef05c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffff800010d2a88c)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (c0d7a5d4)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (c0da4f00)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (c0df6a48)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c0e2e858)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (c000000000d70a30)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (c000000000da8318)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (c000000000e14bdc)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (c000000000e5ba9c)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffe0007d114c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffe0007f5a92)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffe00083c116)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffe00086afb0)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff81959b30)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819827cc)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff819cf1d0)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a0407d)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff81913620)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff8193c28c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff8198bf90)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff819c0e3d)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff819c4300)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819ecf9c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a39c50)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a6eafd)
Location: include/net/sock.h:577
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
In net/ipv4/inet_hashtables.c (ffffffff819cdd6c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/raw.c (ffffffff819f6e8c)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/unix/af_unix.c (ffffffff81a46290)
Location: include/net/sock.h:577
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/raw.c (ffffffff81a7b12d)
Location: include/net/sock.h:577
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
