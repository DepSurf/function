# Function: <code>ipv6_sock_mc_join_ssm</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198e620)
Location: net/ipv6/mcast.c:212
Inline: False
```
**Symbols:**

```
ffffffff8198e620-ffffffff8198e630: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c4ed0)
Location: net/ipv6/mcast.c:212
Inline: False
```
**Symbols:**

```
ffffffff819c4ed0-ffffffff819c4ee0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a33d50)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff81a33d50-ffffffff81a33d60: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a6a8a0)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff81a6a8a0-ffffffff81a6a8b0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b637e0)
Location: net/ipv6/mcast.c:208
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81b637e0-ffffffff81b637f0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b71f90)
Location: net/ipv6/mcast.c:208
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81b71f90-ffffffff81b71fa0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b60ce0)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81b60ce0-ffffffff81b60cf0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81c286a0)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81c286a0-ffffffff81c286b0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81dc5a40)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81dc5a40-ffffffff81dc5a5c: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f96600)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81f96600-ffffffff81f9661c: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff6fd0)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff81ff6fd0-ffffffff81ff6fec: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c4c10)
Location: net/ipv6/mcast.c:239
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_mcast_group_source
```
**Symbols:**

```
ffffffff820c4c10-ffffffff820c4c2c: ipv6_sock_mc_join_ssm (STB_GLOBAL)
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
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d31e08)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffff800010d31e08-ffff800010d31e54: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e34d14)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
c0e34d14-c0e34d30: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e640e0)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
c000000000e640e0-c000000000e640f4: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe0008706de)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffe0008706de-ffffffe000870720: ipv6_sock_mc_join_ssm (STB_GLOBAL)
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
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a09f30)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff81a09f30-ffffffff81a09f40: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c6cf0)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff819c6cf0-ffffffff819c6d00: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a749b0)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff81a749b0-ffffffff81a749c0: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_sock_mc_join_ssm(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a81070)
Location: net/ipv6/mcast.c:208
Inline: False
```
**Symbols:**

```
ffffffff81a81070-ffffffff81a81080: ipv6_sock_mc_join_ssm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
