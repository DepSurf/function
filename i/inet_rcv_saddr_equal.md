# Function: <code>inet_rcv_saddr_equal</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820890)
Location: net/ipv4/inet_connection_sock.c:97
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81820890-ffffffff8182090a: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189f7f0)
Location: net/ipv4/inet_connection_sock.c:97
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff8189f7f0-ffffffff8189f86c: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f42c0)
Location: net/ipv4/inet_connection_sock.c:92
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff818f42c0-ffffffff818f433c: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921dd0)
Location: net/ipv4/inet_connection_sock.c:92
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81921dd0-ffffffff81921e50: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819847b0)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff819847b0-ffffffff81984837: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819baf60)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff819baf60-ffffffff819bafe7: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5c30)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81aa5c30-ffffffff81aa5cb8: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0270)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81ab0270-ffffffff81ab02f8: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b450)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81a9b450-ffffffff81a9b4d8: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b568c0)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81b568c0-ffffffff81b56948: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce46d0)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81ce46d0-ffffffff81ce4799: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea71f0)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81ea71f0-ffffffff81ea72b9: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f05990)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81f05990-ffffffff81f05a59: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9c70)
Location: net/ipv4/inet_connection_sock.c:91
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff81fc9c70-ffffffff81fc9d39: inet_rcv_saddr_equal (STB_GLOBAL)
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
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6ccb0)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
**Symbols:**

```
ffff800010c6ccb0-ffff800010c6cd64: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7b9d8)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
c0d7b9d8-c0d7ba7c: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d72630)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
c000000000d72630-c000000000d726e8: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d24e4)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffe0007d24e4-ffffffe0007d2580: inet_rcv_saddr_equal (STB_GLOBAL)
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
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195add0)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff8195add0-ffffffff8195ae57: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819148c0)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff819148c0-ffffffff81914947: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c55a0)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff819c55a0-ffffffff819c5627: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool inet_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf080)
Location: net/ipv4/inet_connection_sock.c:88
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
**Symbols:**

```
ffffffff819cf080-ffffffff819cf107: inet_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
