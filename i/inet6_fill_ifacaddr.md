# Function: <code>inet6_fill_ifacaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cc7c9)
Location: net/ipv6/addrconf.c:4382
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81839220)
Location: net/ipv6/addrconf.c:4634
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186ac40)
Location: net/ipv6/addrconf.c:4677
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188f1c0)
Location: net/ipv6/addrconf.c:4755
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81910810)
Location: net/ipv6/addrconf.c:4759
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81968634)
Location: net/ipv6/addrconf.c:4885
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199d363)
Location: net/ipv6/addrconf.c:4933
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0977a)
Location: net/ipv6/addrconf.c:4969
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4046a)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34300)
Location: net/ipv6/addrconf.c:5015
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b34300-ffffffff81b34538: inet6_fill_ifacaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b44b50)
Location: net/ipv6/addrconf.c:5044
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b44b50-ffffffff81b44d88: inet6_fill_ifacaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b32820)
Location: net/ipv6/addrconf.c:5048
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b32820-ffffffff81b32a56: inet6_fill_ifacaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5086
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81bf8b70-ffffffff81bf8db3: inet6_fill_ifacaddr (STB_LOCAL)
ffffffff81d3f81c-ffffffff81d3f831: inet6_fill_ifacaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5103
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81d920a0-ffffffff81d922fd: inet6_fill_ifacaddr (STB_LOCAL)
ffffffff81f0c1c2-ffffffff81f0c1d7: inet6_fill_ifacaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5116
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81f607b0-ffffffff81f60a0d: inet6_fill_ifacaddr (STB_LOCAL)
ffffffff820b39cd-ffffffff820b39e2: inet6_fill_ifacaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5122
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81fc05e0-ffffffff81fc083b: inet6_fill_ifacaddr (STB_LOCAL)
ffffffff82134abe-ffffffff82134ad3: inet6_fill_ifacaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifacaddr(struct sk_buff *skb, struct ifacaddr6 *ifaca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5177
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff8208da90-ffffffff8208dced: inet6_fill_ifacaddr (STB_LOCAL)
ffffffff8221657c-ffffffff82216591: inet6_fill_ifacaddr.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d016e4)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e09220)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2b6f8)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084b3b8)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819dfafa)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c8ba)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4a57a)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a564ba)
Location: net/ipv6/addrconf.c:4998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
