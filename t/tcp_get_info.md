# Function: <code>tcp_get_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81766640)
Location: net/ipv4/tcp.c:2635
Inline: False
```
**Symbols:**

```
ffffffff81766640-ffffffff81766965: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d2b60)
Location: net/ipv4/tcp.c:2680
Inline: False
```
**Symbols:**

```
ffffffff817d2b60-ffffffff817d2ecb: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818026f0)
Location: net/ipv4/tcp.c:2737
Inline: False
```
**Symbols:**

```
ffffffff818026f0-ffffffff81802ae9: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81822e10)
Location: net/ipv4/tcp.c:2822
Inline: True
```
**Symbols:**

```
ffffffff81822e10-ffffffff818231fc: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a1f30)
Location: net/ipv4/tcp.c:2919
Inline: True
```
**Symbols:**

```
ffffffff818a1f30-ffffffff818a2313: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f68f0)
Location: net/ipv4/tcp.c:3103
Inline: True
```
**Symbols:**

```
ffffffff818f68f0-ffffffff818f6ceb: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81924150)
Location: net/ipv4/tcp.c:3111
Inline: True
```
**Symbols:**

```
ffffffff81924150-ffffffff8192456f: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81986920)
Location: net/ipv4/tcp.c:3184
Inline: True
```
**Symbols:**

```
ffffffff81986920-ffffffff81986d48: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bd090)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffff819bd090-ffffffff819bd4d4: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa7eb0)
Location: net/ipv4/tcp.c:3372
Inline: True
```
**Symbols:**

```
ffffffff81aa7eb0-ffffffff81aa82ac: tcp_get_info.part.0 (STB_LOCAL)
ffffffff81aa82b0-ffffffff81aa8300: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2420)
Location: net/ipv4/tcp.c:3631
Inline: True
```
**Symbols:**

```
ffffffff81ab2420-ffffffff81ab281c: tcp_get_info.part.0 (STB_LOCAL)
ffffffff81ab2820-ffffffff81ab2870: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d730)
Location: net/ipv4/tcp.c:3685
Inline: True
```
**Symbols:**

```
ffffffff81a9d730-ffffffff81a9db2c: tcp_get_info.part.0 (STB_LOCAL)
ffffffff81a9db30-ffffffff81a9db80: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b59c60)
Location: net/ipv4/tcp.c:3710
Inline: True
```
**Symbols:**

```
ffffffff81b59c60-ffffffff81b5a05c: tcp_get_info.part.0 (STB_LOCAL)
ffffffff81b5a060-ffffffff81b5a0b0: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce7680)
Location: net/ipv4/tcp.c:3729
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81ce7680-ffffffff81ce7afc: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaaf10)
Location: net/ipv4/tcp.c:3829
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81eaaf10-ffffffff81eab3b1: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f09620)
Location: net/ipv4/tcp.c:3723
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81f09620-ffffffff81f09ac1: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fcd8d0)
Location: net/ipv4/tcp.c:3760
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
```
**Symbols:**

```
ffffffff81fcd8d0-ffffffff81fcddfd: tcp_get_info (STB_GLOBAL)
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
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c6f688)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffff800010c6f688-ffff800010c6fa14: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7de4c)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
c0d7de4c-c0d7e1dc: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d757a0)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
c000000000d757a0-c000000000d75bc8: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d4060)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffe0007d4060-ffffffe0007d43bc: tcp_get_info (STB_GLOBAL)
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
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195cf00)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffff8195cf00-ffffffff8195d344: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819169f0)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffff819169f0-ffffffff81916e34: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c76d0)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffff819c76d0-ffffffff819c7b14: tcp_get_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_get_info(struct sock *sk, struct tcp_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d1220)
Location: net/ipv4/tcp.c:3200
Inline: True
```
**Symbols:**

```
ffffffff819d1220-ffffffff819d1664: tcp_get_info (STB_GLOBAL)
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
