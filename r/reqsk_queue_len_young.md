# Function: <code>reqsk_queue_len_young</code>

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
In net/ipv4/inet_connection_sock.c (ffffffff8176555d)
Location: include/net/request_sock.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff8176db65)
Location: include/net/request_sock.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/inet_connection_sock.c (ffffffff817d1b21)
Location: include/net/request_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff817dbec1)
Location: include/net/request_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818019d1)
Location: include/net/request_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81821b7b)
Location: include/net/request_sock.h:223
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818a0b94)
Location: include/net/request_sock.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff818f506e)
Location: include/net/request_sock.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff8192329e)
Location: include/net/request_sock.h:225
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81985c4e)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff819bc0ee)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81aa6c5c)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81ab12c5)
Location: include/net/request_sock.h:234
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9c62b)
Location: include/net/request_sock.h:234
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81b5821a)
Location: include/net/request_sock.h:234
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce633a)
Location: include/net/request_sock.h:236
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea958a)
Location: include/net/request_sock.h:236
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81f07e1a)
Location: include/net/request_sock.h:236
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81fcc17a)
Location: include/net/request_sock.h:236
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffff800010c6d63c)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (c0d7c6ec)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (c000000000d73880)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d3248)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff8195bf5e)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff81915a4e)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff819c672e)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
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
In net/ipv4/inet_connection_sock.c (ffffffff819d027e)
Location: include/net/request_sock.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
</details>
</li>
</ul>

## Differences
