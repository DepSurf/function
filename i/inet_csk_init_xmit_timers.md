# Function: <code>inet_csk_init_xmit_timers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(long unsigned int), void (*delack_handler)(long unsigned int), void (*keepalive_handler)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817640b0)
Location: net/ipv4/inet_connection_sock.c:369
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff817640b0-ffffffff81764143: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(long unsigned int), void (*delack_handler)(long unsigned int), void (*keepalive_handler)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d05f0)
Location: net/ipv4/inet_connection_sock.c:364
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff817d05f0-ffffffff817d0683: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(long unsigned int), void (*delack_handler)(long unsigned int), void (*keepalive_handler)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81800440)
Location: net/ipv4/inet_connection_sock.c:368
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81800440-ffffffff818004d3: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(long unsigned int), void (*delack_handler)(long unsigned int), void (*keepalive_handler)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820020)
Location: net/ipv4/inet_connection_sock.c:494
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81820020-ffffffff818200b3: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189f010)
Location: net/ipv4/inet_connection_sock.c:496
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff8189f010-ffffffff8189f07b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f3a50)
Location: net/ipv4/inet_connection_sock.c:491
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff818f3a50-ffffffff818f3abb: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921570)
Location: net/ipv4/inet_connection_sock.c:507
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81921570-ffffffff819215db: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81983f20)
Location: net/ipv4/inet_connection_sock.c:503
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81983f20-ffffffff81983f8b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ba6d0)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff819ba6d0-ffffffff819ba73b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5230)
Location: net/ipv4/inet_connection_sock.c:549
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81aa5230-ffffffff81aa529b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf840)
Location: net/ipv4/inet_connection_sock.c:549
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81aaf840-ffffffff81aaf8ab: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ab50)
Location: net/ipv4/inet_connection_sock.c:549
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81a9ab50-ffffffff81a9abbb: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b55fc0)
Location: net/ipv4/inet_connection_sock.c:558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81b55fc0-ffffffff81b5602b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d90)
Location: net/ipv4/inet_connection_sock.c:562
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81ce3d90-ffffffff81ce3e0a: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6910)
Location: net/ipv4/inet_connection_sock.c:723
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81ea6910-ffffffff81ea698a: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f050e0)
Location: net/ipv4/inet_connection_sock.c:747
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81f050e0-ffffffff81f0515a: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9430)
Location: net/ipv4/inet_connection_sock.c:748
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81fc9430-ffffffff81fc94aa: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6c428)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffff800010c6c428-ffff800010c6c4b0: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7b0a8)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
c0d7b0a8-c0d7b124: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d71a60)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
c000000000d71a60-c000000000d71b0c: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1bde)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffe0007d1bde-ffffffe0007d1c54: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195a540)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff8195a540-ffffffff8195a5ab: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914030)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81914030-ffffffff8191409b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c4d10)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff819c4d10-ffffffff819c4d7b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_csk_init_xmit_timers(struct sock *sk, void (*retransmit_handler)(struct timer_list *), void (*delack_handler)(struct timer_list *), void (*keepalive_handler)(struct timer_list *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ce7c0)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff819ce7c0-ffffffff819ce82b: inet_csk_init_xmit_timers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*retransmit_handler)(long unsigned int)</code> ➡️ <code>void (*retransmit_handler)(struct timer_list *)</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*delack_handler)(long unsigned int)</code> ➡️ <code>void (*delack_handler)(struct timer_list *)</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*keepalive_handler)(long unsigned int)</code> ➡️ <code>void (*keepalive_handler)(struct timer_list *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
