# Function: <code>ip_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817617b0)
Location: net/ipv4/ip_sockglue.c:1196
Inline: True
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
```
**Symbols:**

```
ffffffff817617b0-ffffffff81761845: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cdac0)
Location: net/ipv4/ip_sockglue.c:1211
Inline: True
```
**Symbols:**

```
ffffffff817cdac0-ffffffff817cdb63: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fd820)
Location: net/ipv4/ip_sockglue.c:1251
Inline: True
```
**Symbols:**

```
ffffffff817fd820-ffffffff817fd8c3: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181dc60)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff8181dc60-ffffffff8181dd03: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189cbd0)
Location: net/ipv4/ip_sockglue.c:1242
Inline: True
```
**Symbols:**

```
ffffffff8189cbd0-ffffffff8189cc4b: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818f10a0)
Location: net/ipv4/ip_sockglue.c:1241
Inline: True
```
**Symbols:**

```
ffffffff818f10a0-ffffffff818f112e: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191ec00)
Location: net/ipv4/ip_sockglue.c:1238
Inline: True
```
**Symbols:**

```
ffffffff8191ec00-ffffffff8191ec8e: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81981500)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff81981500-ffffffff8198159c: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b7d20)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff819b7d20-ffffffff819b7dd1: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa26e0)
Location: net/ipv4/ip_sockglue.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81aa26e0-ffffffff81aa2791: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aac990)
Location: net/ipv4/ip_sockglue.c:1415
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
```
**Symbols:**

```
ffffffff81aac990-ffffffff81aaca61: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a97be0)
Location: net/ipv4/ip_sockglue.c:1415
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
```
**Symbols:**

```
ffffffff81a97be0-ffffffff81a97cb1: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b53070)
Location: net/ipv4/ip_sockglue.c:1415
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
```
**Symbols:**

```
ffffffff81b53070-ffffffff81b53141: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ce0ff0)
Location: net/ipv4/ip_sockglue.c:1426
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81ce0ff0-ffffffff81ce10de: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ea13f0)
Location: net/ipv4/ip_sockglue.c:1427
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81ea13f0-ffffffff81ea14d4: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81effc00)
Location: net/ipv4/ip_sockglue.c:1449
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81effc00-ffffffff81effce4: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc3dd0)
Location: net/ipv4/ip_sockglue.c:1405
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
  - net/ipv4/udp.c:udp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
```
**Symbols:**

```
ffffffff81fc3dd0-ffffffff81fc3e6c: ip_setsockopt (STB_GLOBAL)
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
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c690b8)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffff800010c690b8-ffff800010c691a8: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d783b0)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
c0d783b0-c0d78488: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6db50)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
c000000000d6db50-c000000000d6dc90: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cf118)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffe0007cf118-ffffffe0007cf1c6: ip_setsockopt (STB_GLOBAL)
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
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81957b90)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff81957b90-ffffffff81957c41: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81911680)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff81911680-ffffffff81911731: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c2360)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff819c2360-ffffffff819c2411: ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819cbd60)
Location: net/ipv4/ip_sockglue.c:1240
Inline: True
```
**Symbols:**

```
ffffffff819cbd60-ffffffff819cbe11: ip_setsockopt (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
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
