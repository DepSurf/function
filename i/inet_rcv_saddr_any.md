# Function: <code>inet_rcv_saddr_any</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81923530)
Location: net/ipv4/inet_connection_sock.c:110
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81923530-ffffffff81923557: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81985ee0)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81985ee0-ffffffff81985f07: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bc6f0)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819bc6f0-ffffffff819bc717: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa7170)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81aa7170-ffffffff81aa7197: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1800)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/inet_hashtables.c:inet_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
  - net/ipv4/udp.c:udp_reuseport_add_sock
```
**Symbols:**

```
ffffffff81ab1800-ffffffff81ab1827: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ca70)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81a9ca70-ffffffff81a9ca97: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b587a0)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81b587a0-ffffffff81b587c7: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6970)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ce6970-ffffffff81ce69a3: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9bd0)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ea9bd0-ffffffff81ea9c03: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f08430)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81f08430-ffffffff81f08463: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fcc790)
Location: net/ipv4/inet_connection_sock.c:111
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81fcc790-ffffffff81fcc7c3: inet_rcv_saddr_any (STB_GLOBAL)
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
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6e7e8)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffff800010c6e7e8-ffff800010c6e840: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7d38c)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c0d7d38c-c0d7d3e4: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d74910)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c000000000d74910-c000000000d74958: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d3704)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffe0007d3704-ffffffe0007d3752: inet_rcv_saddr_any (STB_GLOBAL)
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
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195c560)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8195c560-ffffffff8195c587: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81916050)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81916050-ffffffff81916077: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c6d30)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819c6d30-ffffffff819c6d57: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool inet_rcv_saddr_any(const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819d0880)
Location: net/ipv4/inet_connection_sock.c:106
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819d0880-ffffffff819d08a7: inet_rcv_saddr_any (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
