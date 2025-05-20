# Function: <code>__tcp_md5_do_lookup</code>

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
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193dcf0)
Location: net/ipv4/tcp_ipv4.c:980
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff8193dcf0-ffffffff8193de1a: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a2110)
Location: net/ipv4/tcp_ipv4.c:981
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff819a2110-ffffffff819a223f: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d8ce0)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff819d8ce0-ffffffff819d8e0f: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5720)
Location: net/ipv4/tcp_ipv4.c:1013
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81ac5720-ffffffff81ac5848: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1390)
Location: net/ipv4/tcp_ipv4.c:1026
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81ad1390-ffffffff81ad14b8: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abc380)
Location: net/ipv4/tcp_ipv4.c:1041
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81abc380-ffffffff81abc4a7: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1055
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81d3b671-ffffffff81d3b6c1: __tcp_md5_do_lookup.cold (STB_LOCAL)
ffffffff81b79480-ffffffff81b795ca: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1063
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81f07f4d-ffffffff81f07f91: __tcp_md5_do_lookup.cold (STB_LOCAL)
ffffffff81d091d0-ffffffff81d09333: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1074
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff820af9f6-ffffffff820afa3a: __tcp_md5_do_lookup.cold (STB_LOCAL)
ffffffff81ece390-ffffffff81ece4f3: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1081
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff82130d72-ffffffff82130db6: __tcp_md5_do_lookup.cold (STB_LOCAL)
ffffffff81f2d7f0-ffffffff81f2d953: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, int l3index, const union tcp_ao_addr *addr, int family, bool any_l3index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1240
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff8221256a-ffffffff822125c0: __tcp_md5_do_lookup.cold (STB_LOCAL)
ffffffff81ff2270-ffffffff81ff2416: __tcp_md5_do_lookup (STB_GLOBAL)
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
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8b408)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffff800010c8b408-ffff800010c8b53c: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d991c8)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
c0d991c8-c0d99304: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9a540)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
c000000000d9a540-c000000000d9a7a8: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007eaea8)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffe0007eaea8-ffffffe0007eb010: __tcp_md5_do_lookup (STB_GLOBAL)
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
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81978b50)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81978b50-ffffffff81978c7f: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81932610)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff81932610-ffffffff8193273f: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e3320)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff819e3320-ffffffff819e344f: __tcp_md5_do_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcp_md5sig_key *__tcp_md5_do_lookup(const struct sock *sk, const union tcp_md5_addr *addr, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ed440)
Location: net/ipv4/tcp_ipv4.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
```
**Symbols:**

```
ffffffff819ed440-ffffffff819ed56f: __tcp_md5_do_lookup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family</code> ➡️ <code>sk, l3index, addr, family</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool any_l3index</code>
</li>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr *addr</code> ➡️ <code>const union tcp_ao_addr *addr</code>
</li>
</ul>
</details>
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
