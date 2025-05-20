# Function: <code>inet_csk_reqsk_queue_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817651a0)
Location: net/ipv4/inet_connection_sock.c:540
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff817651a0-ffffffff817653b9: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d1720)
Location: net/ipv4/inet_connection_sock.c:531
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff817d1720-ffffffff817d1935: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818015d0)
Location: net/ipv4/inet_connection_sock.c:535
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818015d0-ffffffff818017e5: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818214f0)
Location: net/ipv4/inet_connection_sock.c:661
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818214f0-ffffffff81821693: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818a08b0)
Location: net/ipv4/inet_connection_sock.c:660
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818a08b0-ffffffff818a0a77: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f4d90)
Location: net/ipv4/inet_connection_sock.c:655
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818f4d90-ffffffff818f4f57: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81922fc0)
Location: net/ipv4/inet_connection_sock.c:674
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81922fc0-ffffffff81923187: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81985960)
Location: net/ipv4/inet_connection_sock.c:669
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81985960-ffffffff81985b3c: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe00)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819bbe00-ffffffff819bbfdc: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6cb8)
Location: net/ipv4/inet_connection_sock.c:709
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81aa67a0-ffffffff81aa688a: inet_csk_reqsk_queue_drop.part.0 (STB_LOCAL)
ffffffff81aa69e0-ffffffff81aa6a16: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1351)
Location: net/ipv4/inet_connection_sock.c:708
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81ab0df0-ffffffff81ab0eda: inet_csk_reqsk_queue_drop.part.0 (STB_LOCAL)
ffffffff81ab1030-ffffffff81ab1079: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c250)
Location: net/ipv4/inet_connection_sock.c:708
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81a9c250-ffffffff81a9c4d6: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b57b10)
Location: net/ipv4/inet_connection_sock.c:777
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81b57b10-ffffffff81b57d96: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b10)
Location: net/ipv4/inet_connection_sock.c:781
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81ce5b10-ffffffff81ce5d83: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d20)
Location: net/ipv4/inet_connection_sock.c:943
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81ea8d20-ffffffff81ea8fac: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f075a0)
Location: net/ipv4/inet_connection_sock.c:967
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81f075a0-ffffffff81f0783e: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb900)
Location: net/ipv4/inet_connection_sock.c:968
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81fcb900-ffffffff81fcbb9e: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6d2a0)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffff800010c6d2a0-ffff800010c6d51c: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7c270)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
c0d7c270-c0d7c4dc: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d73230)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
c000000000d73230-c000000000d73570: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2f82)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffe0007d2f82-ffffffe0007d3140: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195bc70)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff8195bc70-ffffffff8195be4c: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81915760)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81915760-ffffffff8191593c: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c6440)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819c6440-ffffffff819c661c: inet_csk_reqsk_queue_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock *sk, struct request_sock *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cff60)
Location: net/ipv4/inet_connection_sock.c:689
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819cff60-ffffffff819d0164: inet_csk_reqsk_queue_drop (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
