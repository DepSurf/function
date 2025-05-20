# Function: <code>tcp_write_queue_purge</code>

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
In net/ipv4/tcp.c (ffffffff817680b1)
Location: include/net/tcp.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c913)
Location: include/net/tcp.h:1449
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff817d496c)
Location: include/net/tcp.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea220)
Location: include/net/tcp.h:1462
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff818046b3)
Location: include/net/tcp.h:1533
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818a50)
Location: include/net/tcp.h:1533
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In net/ipv4/tcp.c (ffffffff81824932)
Location: include/net/tcp.h:1584
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183921a)
Location: include/net/tcp.h:1584
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a6570)
Location: net/ipv4/tcp.c:2351
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff818a6570-ffffffff818a6752: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fb610)
Location: net/ipv4/tcp.c:2520
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff818fb610-ffffffff818fb7fa: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81929560)
Location: net/ipv4/tcp.c:2522
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81929560-ffffffff81929754: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198c490)
Location: net/ipv4/tcp.c:2533
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8198c490-ffffffff8198c812: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c2de0)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff819c2de0-ffffffff819c3181: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aae3f0)
Location: net/ipv4/tcp.c:2608
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81aae3f0-ffffffff81aae843: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab8690)
Location: net/ipv4/tcp.c:2861
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81ab8690-ffffffff81ab8a8e: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa3990)
Location: net/ipv4/tcp.c:2915
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81aa3990-ffffffff81aa3d3a: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5fb40)
Location: net/ipv4/tcp.c:2940
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81b5fb40-ffffffff81b5feea: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cee600)
Location: net/ipv4/tcp.c:2968
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81cee600-ffffffff81cee910: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb1850)
Location: net/ipv4/tcp.c:3065
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81eb1850-ffffffff81eb1b70: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0fee0)
Location: net/ipv4/tcp.c:2951
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81f0fee0-ffffffff81f10204: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd40e0)
Location: net/ipv4/tcp.c:2963
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81fd40e0-ffffffff81fd4404: tcp_write_queue_purge (STB_GLOBAL)
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
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c75be8)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffff800010c75be8-ffff800010c75ef4: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d84284)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
c0d84284-c0d845b0: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7d460)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
c000000000d7d460-c000000000d7d8bc: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d8e08)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffe0007d8e08-ffffffe0007d90ea: tcp_write_queue_purge (STB_GLOBAL)
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
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81962c50)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81962c50-ffffffff81962ff1: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191c740)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8191c740-ffffffff8191cae1: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cd420)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff819cd420-ffffffff819cd7c1: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d6fb0)
Location: net/ipv4/tcp.c:2536
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_timer.c:tcp_write_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff819d6fb0-ffffffff819d7351: tcp_write_queue_purge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
