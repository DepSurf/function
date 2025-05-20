# Function: <code>inetdev_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8178f770)
Location: net/ipv4/devinet.c:523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8178f770-ffffffff8178f790: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fe3f5)
Location: net/ipv4/devinet.c:527
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff817fcd10-ffffffff817fcd30: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182f355)
Location: net/ipv4/devinet.c:527
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8182dc70-ffffffff8182dc90: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818507cc)
Location: net/ipv4/devinet.c:546
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
```
**Symbols:**

```
ffffffff8184f140-ffffffff8184f160: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d03fc)
Location: net/ipv4/devinet.c:553
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
```
**Symbols:**

```
ffffffff818ced70-ffffffff818ced90: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8192693f)
Location: net/ipv4/devinet.c:554
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819251b0-ffffffff819251d0: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819559d2)
Location: net/ipv4/devinet.c:564
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81953fc0-ffffffff81953fdc: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819ba381)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819b8a20-ffffffff819b8a3c: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0f11)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819ef720-ffffffff819ef73c: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81adee90)
Location: net/ipv4/devinet.c:588
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81add680-ffffffff81add69c: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aebc97)
Location: net/ipv4/devinet.c:588
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81aea3a0-ffffffff81aea3cd: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad72f7)
Location: net/ipv4/devinet.c:588
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81ad5af0-ffffffff81ad5b1d: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b96b07)
Location: net/ipv4/devinet.c:588
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81b949c0-ffffffff81b949ed: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d287d7)
Location: net/ipv4/devinet.c:589
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81d263e0-ffffffff81d26426: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef0217)
Location: net/ipv4/devinet.c:590
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81eedc30-ffffffff81eedc76: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4fc67)
Location: net/ipv4/devinet.c:590
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81f4d5f0-ffffffff81f4d636: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82015dd4)
Location: net/ipv4/devinet.c:591
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff82013700-ffffffff82013746: inetdev_by_index (STB_GLOBAL)
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
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca7194)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffff800010ca5568-ffff800010ca55a4: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db3898)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
c0db1eb8-c0db1edc: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbb8d0)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
c000000000db93e0-c000000000db9420: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe00080239a)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffe000800e72-ffffffe000800eaa: inetdev_by_index (STB_GLOBAL)
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
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81990cb1)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff8198f4c0-ffffffff8198f4dc: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194a771)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81948f80-ffffffff81948f9c: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fb551)
Location: net/ipv4/devinet.c:587
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819f9d60-ffffffff819f9d7c: inetdev_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct in_device *inetdev_by_index(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a04050)
Location: net/ipv4/devinet.c:587
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81a04050-ffffffff81a04090: inetdev_by_index (STB_GLOBAL)
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
