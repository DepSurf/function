# Function: <code>sock_owned_by_user_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (0)
Location: include/net/sock.h:1517
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819b44b6)
Location: include/net/sock.h:1530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819eb4e6)
Location: include/net/sock.h:1569
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a5a6bc)
Location: include/net/sock.h:1579
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a9130c)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8c77c)
Location: include/net/sock.h:1638
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b9c3cc)
Location: include/net/sock.h:1656
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8b48c)
Location: include/net/sock.h:1672
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81c5772c)
Location: include/net/sock.h:1712
Inline: True
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
In net/core/sock.c (ffffffff81bf0a33)
Location: include/net/sock.h:1801
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/ipv4/tcp_output.c (ffffffff81d046b1)
Location: include/net/sock.h:1801
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/strparser/strparser.c (ffffffff81df8d2c)
Location: include/net/sock.h:1801
Inline: True
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
In net/core/sock.c (ffffffff81d9d013)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/ipv4/tcp_output.c (ffffffff81ec962f)
Location: include/net/sock.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/strparser/strparser.c (ffffffff81fcd30c)
Location: include/net/sock.h:1822
Inline: True
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
In net/core/sock.c (ffffffff81e0b863)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/ipv4/tcp_output.c (ffffffff81f2817f)
Location: include/net/sock.h:1813
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/strparser/strparser.c (ffffffff82048c3c)
Location: include/net/sock.h:1813
Inline: True
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
In net/core/sock.c (ffffffff81ec8253)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8cf9)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/strparser/strparser.c (ffffffff8211afbc)
Location: include/net/sock.h:1788
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffff800010d5eed8)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c0e5eac8)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c000000000e998ec)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffe000894672)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a3099c)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819edb8c)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a9c54c)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81aa872c)
Location: include/net/sock.h:1589
Inline: True
```
</details>
</li>
</ul>

## Differences
