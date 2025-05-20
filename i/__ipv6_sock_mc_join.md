# Function: <code>__ipv6_sock_mc_join</code>

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
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198e3f0)
Location: net/ipv6/mcast.c:137
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff8198e3f0-ffffffff8198e5f3: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c4ca0)
Location: net/ipv6/mcast.c:137
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819c4ca0-ffffffff819c4ea3: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a33b10)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a33b10-ffffffff81a33d10: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a6a660)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a6a660-ffffffff81a6a860: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b635a0)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b635a0-ffffffff81b637a0: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b71d40)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b71d40-ffffffff81b71f4a: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b60240)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b60240-ffffffff81b60435: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81c27b50-ffffffff81c27d5e: __ipv6_sock_mc_join (STB_LOCAL)
ffffffff81d40a24-ffffffff81d40a5b: __ipv6_sock_mc_join.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81dc4ef0-ffffffff81dc513f: __ipv6_sock_mc_join (STB_LOCAL)
ffffffff81f0d40e-ffffffff81f0d445: __ipv6_sock_mc_join.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81f95a60-ffffffff81f95caf: __ipv6_sock_mc_join (STB_LOCAL)
ffffffff820b4857-ffffffff820b488e: __ipv6_sock_mc_join.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81ff6410-ffffffff81ff6679: __ipv6_sock_mc_join (STB_LOCAL)
ffffffff821358b0-ffffffff821358de: __ipv6_sock_mc_join.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:169
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff820c4050-ffffffff820c42b9: __ipv6_sock_mc_join (STB_LOCAL)
ffffffff822173bd-ffffffff822173eb: __ipv6_sock_mc_join.cold (STB_LOCAL)
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
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d31718)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffff800010d31718-ffff800010d31928: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e34ab4)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
c0e34ab4-c0e34cd4: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e63dc0)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
c000000000e63dc0-c000000000e64098: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe00086ff78)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffe00086ff78-ffffffe000870154: __ipv6_sock_mc_join (STB_LOCAL)
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
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a09cf0)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a09cf0-ffffffff81a09ef0: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c6ab0)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819c6ab0-ffffffff819c6cb0: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a74770)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a74770-ffffffff81a74970: __ipv6_sock_mc_join (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ipv6_sock_mc_join(struct sock *sk, int ifindex, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a80e20)
Location: net/ipv6/mcast.c:133
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_sock_mc_join_ssm
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a80e20-ffffffff81a8102f: __ipv6_sock_mc_join (STB_LOCAL)
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
