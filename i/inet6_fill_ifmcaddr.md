# Function: <code>inet6_fill_ifmcaddr</code>

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
In net/ipv6/addrconf.c (ffffffff817cca60)
Location: net/ipv6/addrconf.c:4356
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
In net/ipv6/addrconf.c (ffffffff818393c6)
Location: net/ipv6/addrconf.c:4608
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
In net/ipv6/addrconf.c (ffffffff8186ade6)
Location: net/ipv6/addrconf.c:4651
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
In net/ipv6/addrconf.c (ffffffff8188f3dd)
Location: net/ipv6/addrconf.c:4729
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
In net/ipv6/addrconf.c (ffffffff81910a2d)
Location: net/ipv6/addrconf.c:4733
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
In net/ipv6/addrconf.c (ffffffff819687b0)
Location: net/ipv6/addrconf.c:4859
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
In net/ipv6/addrconf.c (ffffffff8199d5b6)
Location: net/ipv6/addrconf.c:4902
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
In net/ipv6/addrconf.c (ffffffff81a09576)
Location: net/ipv6/addrconf.c:4938
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
In net/ipv6/addrconf.c (ffffffff81a40266)
Location: net/ipv6/addrconf.c:4967
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
int inet6_fill_ifmcaddr(struct sk_buff *skb, struct ifmcaddr6 *ifmca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b35c20)
Location: net/ipv6/addrconf.c:4984
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b35c20-ffffffff81b35df9: inet6_fill_ifmcaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_fill_ifmcaddr(struct sk_buff *skb, struct ifmcaddr6 *ifmca, struct inet6_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b45100)
Location: net/ipv6/addrconf.c:5011
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
**Symbols:**

```
ffffffff81b45100-ffffffff81b452d9: inet6_fill_ifmcaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3301d)
Location: net/ipv6/addrconf.c:5015
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf92bd)
Location: net/ipv6/addrconf.c:5053
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d926ac)
Location: net/ipv6/addrconf.c:5070
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f60ddc)
Location: net/ipv6/addrconf.c:5083
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc0c59)
Location: net/ipv6/addrconf.c:5089
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208e11b)
Location: net/ipv6/addrconf.c:5144
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
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
In net/ipv6/addrconf.c (ffff800010d014ec)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (c0e09044)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (c000000000e2b4b8)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (ffffffe00084b2d4)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (ffffffff819df8f6)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (ffffffff8199c6b6)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (ffffffff81a4a376)
Location: net/ipv6/addrconf.c:4967
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
In net/ipv6/addrconf.c (ffffffff81a562b6)
Location: net/ipv6/addrconf.c:4967
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
</ul>
