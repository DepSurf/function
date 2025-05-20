# Function: <code>tcp_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81767fa0)
Location: net/ipv4/tcp.c:2914
Inline: True
```
**Symbols:**

```
ffffffff81767fa0-ffffffff81767fce: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d45a0)
Location: net/ipv4/tcp.c:2990
Inline: True
```
**Symbols:**

```
ffffffff817d45a0-ffffffff817d45ce: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818042e0)
Location: net/ipv4/tcp.c:3083
Inline: True
```
**Symbols:**

```
ffffffff818042e0-ffffffff8180430e: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81823a20)
Location: net/ipv4/tcp.c:3193
Inline: False
```
**Symbols:**

```
ffffffff81823a20-ffffffff81823a4e: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a34c0)
Location: net/ipv4/tcp.c:3329
Inline: False
```
**Symbols:**

```
ffffffff818a34c0-ffffffff818a34f6: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f86f0)
Location: net/ipv4/tcp.c:3544
Inline: True
```
**Symbols:**

```
ffffffff818f86f0-ffffffff818f8726: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81925320)
Location: net/ipv4/tcp.c:3590
Inline: True
```
**Symbols:**

```
ffffffff81925320-ffffffff81925356: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819888c0)
Location: net/ipv4/tcp.c:3669
Inline: True
```
**Symbols:**

```
ffffffff819888c0-ffffffff819888f6: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bfd10)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffff819bfd10-ffffffff819bfd46: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aab010)
Location: net/ipv4/tcp.c:3879
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81aab010-ffffffff81aab046: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab8060)
Location: net/ipv4/tcp.c:4144
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81ab8060-ffffffff81ab8096: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa3310)
Location: net/ipv4/tcp.c:4249
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81aa3310-ffffffff81aa3346: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5f4f0)
Location: net/ipv4/tcp.c:4274
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81b5f4f0-ffffffff81b5f526: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cedf30)
Location: net/ipv4/tcp.c:4296
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81cedf30-ffffffff81cedf8b: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb4c00)
Location: net/ipv4/tcp.c:4401
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81eb4c00-ffffffff81eb4c64: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f130b0)
Location: net/ipv4/tcp.c:4297
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81f130b0-ffffffff81f13114: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd7440)
Location: net/ipv4/tcp.c:4365
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81fd7440-ffffffff81fd74a4: tcp_getsockopt (STB_GLOBAL)
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
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c73de8)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffff800010c73de8-ffff800010c73e7c: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d824f0)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
c0d824f0-c0d82548: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d79ff0)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
c000000000d79ff0-c000000000d7a058: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d5c98)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffe0007d5c98-ffffffe0007d5cfa: tcp_getsockopt (STB_GLOBAL)
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
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195fb80)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffff8195fb80-ffffffff8195fbb6: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81919670)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffff81919670-ffffffff819196a6: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819ca350)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffff819ca350-ffffffff819ca386: tcp_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d3ec0)
Location: net/ipv4/tcp.c:3687
Inline: True
```
**Symbols:**

```
ffffffff819d3ec0-ffffffff819d3ef6: tcp_getsockopt (STB_GLOBAL)
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
