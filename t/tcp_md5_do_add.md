# Function: <code>tcp_md5_do_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177bea0)
Location: net/ipv4/tcp_ipv4.c:915
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff8177bea0-ffffffff8177c1a8: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e96e0)
Location: net/ipv4/tcp_ipv4.c:923
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff817e96e0-ffffffff817e99eb: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81819990)
Location: net/ipv4/tcp_ipv4.c:929
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81819990-ffffffff81819c9b: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81839be0)
Location: net/ipv4/tcp_ipv4.c:985
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81839be0-ffffffff81839ef5: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b92f0)
Location: net/ipv4/tcp_ipv4.c:989
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff818b92f0-ffffffff818b9605: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190e640)
Location: net/ipv4/tcp_ipv4.c:1051
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff8190e640-ffffffff8190e94d: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193ca30)
Location: net/ipv4/tcp_ipv4.c:1061
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff8193ca30-ffffffff8193cd50: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a0e90)
Location: net/ipv4/tcp_ipv4.c:1062
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff819a0e90-ffffffff819a1193: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d7b40)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff819d7b40-ffffffff819d7e43: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac3ba0)
Location: net/ipv4/tcp_ipv4.c:1103
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81ac3ba0-ffffffff81ac3ea2: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81acf630)
Location: net/ipv4/tcp_ipv4.c:1116
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81acf630-ffffffff81acf932: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81aba780)
Location: net/ipv4/tcp_ipv4.c:1131
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81aba780-ffffffff81abaa83: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b77a60)
Location: net/ipv4/tcp_ipv4.c:1146
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81b77a60-ffffffff81b77dd8: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d07530)
Location: net/ipv4/tcp_ipv4.c:1154
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81d07530-ffffffff81d078c6: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ece070)
Location: net/ipv4/tcp_ipv4.c:1233
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81ece070-ffffffff81ece18d: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d4f0)
Location: net/ipv4/tcp_ipv4.c:1240
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81f2d4f0-ffffffff81f2d608: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_ao_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2850)
Location: net/ipv4/tcp_ipv4.c:1396
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81ff2850-ffffffff81ff29b0: tcp_md5_do_add (STB_GLOBAL)
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
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8aa60)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffff800010c8aa60-ffff800010c8ac0c: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9aa7c)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
c0d9aa7c-c0d9abdc: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d992c0)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
c000000000d992c0-c000000000d99504: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebc4e)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffe0007ebc4e-ffffffe0007ebdac: tcp_md5_do_add (STB_GLOBAL)
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
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819779b0)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff819779b0-ffffffff81977cb3: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81931470)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff81931470-ffffffff81931773: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e2180)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff819e2180-ffffffff819e2483: tcp_md5_do_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819ebed0)
Location: net/ipv4/tcp_ipv4.c:1069
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
**Symbols:**

```
ffffffff819ebed0-ffffffff819ec1d3: tcp_md5_do_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 prefixlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, newkey, newkeylen, gfp</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int l3index</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, prefixlen, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, l3index, newkey, newkeylen, gfp</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, addr, family, prefixlen, l3index, newkey, newkeylen, gfp</code> ➡️ <code>sk, addr, family, prefixlen, l3index, flags, newkey, newkeylen, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
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
