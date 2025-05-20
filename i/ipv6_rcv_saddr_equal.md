# Function: <code>ipv6_rcv_saddr_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e1790)
Location: net/ipv6/udp.c:79
Inline: False
Direct callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
```
**Symbols:**

```
ffffffff817e1790-ffffffff817e18be: ipv6_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81872e20)
Location: net/ipv6/inet6_hashtables.c:282
Inline: False
Direct callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
```
**Symbols:**

```
ffffffff81872e20-ffffffff81872f54: ipv6_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock *sk, const struct sock *sk2, bool match_wildcard);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818a7440)
Location: net/ipv6/inet6_hashtables.c:285
Inline: False
Direct callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
  - net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict
```
**Symbols:**

```
ffffffff818a7440-ffffffff818a7574: ipv6_rcv_saddr_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8181feb0)
Location: net/ipv4/inet_connection_sock.c:42
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8181feb0-ffffffff8181ffdc: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189eea0)
Location: net/ipv4/inet_connection_sock.c:42
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8189eea0-ffffffff8189efc8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f3920)
Location: net/ipv4/inet_connection_sock.c:37
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff818f3920-ffffffff818f3a4c: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921440)
Location: net/ipv4/inet_connection_sock.c:37
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81921440-ffffffff8192156c: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81983db0)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81983db0-ffffffff81983ed8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ba560)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819ba560-ffffffff819ba688: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa50b0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81aa50b0-ffffffff81aa51e4: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf6c0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81aaf6c0-ffffffff81aaf7f4: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9a9d0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81a9a9d0-ffffffff81a9ab04: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b55e40)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81b55e40-ffffffff81b55f74: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3bb0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81ce3bb0-ffffffff81ce3d34: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea65f0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81ea65f0-ffffffff81ea6774: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f04dc0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81f04dc0-ffffffff81f04f44: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc90d0)
Location: net/ipv4/inet_connection_sock.c:34
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse
```
**Symbols:**

```
ffffffff81fc90d0-ffffffff81fc9254: ipv6_rcv_saddr_equal (STB_LOCAL)
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
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6c238)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffff800010c6c238-ffff800010c6c3bc: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7ae9c)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c0d7ae9c-c0d7b028: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d717b0)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
c000000000d717b0-c000000000d719f8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1a62)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffe0007d1a62-ffffffe0007d1b80: ipv6_rcv_saddr_equal (STB_LOCAL)
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
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195a3d0)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff8195a3d0-ffffffff8195a4f8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81913ec0)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff81913ec0-ffffffff81913fe8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c4ba0)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819c4ba0-ffffffff819c4cc8: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr *sk1_rcv_saddr6, const struct in6_addr *sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ce650)
Location: net/ipv4/inet_connection_sock.c:33
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
**Symbols:**

```
ffffffff819ce650-ffffffff819ce778: ipv6_rcv_saddr_equal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool match_wildcard</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr *sk1_rcv_saddr6</code>
</li>
<li>
<b>Param added. </b>
<code>const struct in6_addr *sk2_rcv_saddr6</code>
</li>
<li>
<b>Param added. </b>
<code>__be32 sk1_rcv_saddr</code>
</li>
<li>
<b>Param added. </b>
<code>__be32 sk2_rcv_saddr</code>
</li>
<li>
<b>Param added. </b>
<code>bool sk1_ipv6only</code>
</li>
<li>
<b>Param added. </b>
<code>bool sk2_ipv6only</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock *sk2</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, sk2, match_wildcard</code> ➡️ <code>sk1_rcv_saddr6, sk2_rcv_saddr6, sk1_rcv_saddr, sk2_rcv_saddr, sk1_ipv6only, sk2_ipv6only, match_wildcard</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool match_sk1_wildcard</code>
</li>
<li>
<b>Param added. </b>
<code>bool match_sk2_wildcard</code>
</li>
<li>
<b>Param removed. </b>
<code>bool match_wildcard</code>
</li>
</ul>
</details>
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
