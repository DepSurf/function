# Function: <code>ipv6_add_addr_hash</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81911740)
Location: net/ipv6/addrconf.c:978
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81968b76)
Location: net/ipv6/addrconf.c:966
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff8199e498)
Location: net/ipv6/addrconf.c:980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81a0a539)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81a411e9)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_add_addr_hash(struct net_device *dev, struct inet6_ifaddr *ifa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b351b0)
Location: net/ipv6/addrconf.c:1014
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81b351b0-ffffffff81b352dd: ipv6_add_addr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_add_addr_hash(struct net_device *dev, struct inet6_ifaddr *ifa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b438c0)
Location: net/ipv6/addrconf.c:1014
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
**Symbols:**

```
ffffffff81b438c0-ffffffff81b439ed: ipv6_add_addr_hash (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b33743)
Location: net/ipv6/addrconf.c:1016
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81bf9db3)
Location: net/ipv6/addrconf.c:1023
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81d9318b)
Location: net/ipv6/addrconf.c:1031
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81f6191b)
Location: net/ipv6/addrconf.c:1031
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81fc1747)
Location: net/ipv6/addrconf.c:1030
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff8208ec7f)
Location: net/ipv6/addrconf.c:1049
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffff800010d02c34)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (c0e09934)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (c000000000e2a678)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffe00084bfc0)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff819e0879)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff8199d639)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81a4b2f9)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/ipv6/addrconf.c (ffffffff81a57254)
Location: net/ipv6/addrconf.c:1014
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
