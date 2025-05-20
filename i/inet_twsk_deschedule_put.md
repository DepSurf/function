# Function: <code>inet_twsk_deschedule_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81763800)
Location: net/ipv4/inet_timewait_sock.c:214
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81763800-ffffffff81763830: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfcc0)
Location: net/ipv4/inet_timewait_sock.c:215
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff817cfcc0-ffffffff817cfcf0: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffab0)
Location: net/ipv4/inet_timewait_sock.c:215
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff817ffab0-ffffffff817ffae0: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fcc0)
Location: net/ipv4/inet_timewait_sock.c:215
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff8181fcc0-ffffffff8181fcf0: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ec60)
Location: net/ipv4/inet_timewait_sock.c:211
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff8189ec60-ffffffff8189ec90: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff818f36a0)
Location: net/ipv4/inet_timewait_sock.c:211
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff818f36a0-ffffffff818f36db: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819211c0)
Location: net/ipv4/inet_timewait_sock.c:211
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff819211c0-ffffffff819211fb: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81983b90)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81983b90-ffffffff81983bce: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba370)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff819ba370-ffffffff819ba3ae: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f4d)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81aa4e50-ffffffff81aa4e92: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf5b8)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81aaf4b0-ffffffff81aaf4f2: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8c0)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81a9a7c0-ffffffff81a9a802: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d30)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81b55c30-ffffffff81b55c72: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a3c)
Location: net/ipv4/inet_timewait_sock.c:211
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81ce3920-ffffffff81ce3971: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6478)
Location: net/ipv4/inet_timewait_sock.c:236
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81ea6320-ffffffff81ea6371: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c50)
Location: net/ipv4/inet_timewait_sock.c:233
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81f04b00-ffffffff81f04b51: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f58)
Location: net/ipv4/inet_timewait_sock.c:218
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81fc8e00-ffffffff81fc8e51: inet_twsk_deschedule_put (STB_GLOBAL)
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
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffff800010c6beb0)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffff800010c6beb0-ffff800010c6bf04: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c0d7acd4)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
c0d7acd4-c0d7ad14: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c000000000d71480)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
c000000000d71480-c000000000d714f0: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d185a)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffe0007d185a-ffffffe0007d18ca: inet_twsk_deschedule_put (STB_GLOBAL)
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
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a1e0)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff8195a1e0-ffffffff8195a21e: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81913cd0)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81913cd0-ffffffff81913d0e: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819c49b0)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff819c49b0-ffffffff819c49ee: inet_twsk_deschedule_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_twsk_deschedule_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce430)
Location: net/ipv4/inet_timewait_sock.c:212
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff819ce430-ffffffff819ce46e: inet_twsk_deschedule_put (STB_GLOBAL)
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
