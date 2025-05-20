# Function: <code>arp_invalidate</code>

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
In net/ipv4/arp.c (ffffffff8178c69d)
Location: net/ipv4/arp.c:1065
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff817f9c9d)
Location: net/ipv4/arp.c:1078
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff8182ab6d)
Location: net/ipv4/arp.c:1078
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff8184bd78)
Location: net/ipv4/arp.c:1112
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff818cba18)
Location: net/ipv4/arp.c:1117
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81921f06)
Location: net/ipv4/arp.c:1117
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81950d36)
Location: net/ipv4/arp.c:1117
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff819b561c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff819ec33c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ada27c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ae6d1c)
Location: net/ipv4/arp.c:1119
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81ad1feb)
Location: net/ipv4/arp.c:1119
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81b90c3b)
Location: net/ipv4/arp.c:1119
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arp_invalidate(struct net_device *dev, __be32 ip, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81d234f0)
Location: net/ipv4/arp.c:1119
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81d234f0-ffffffff81d2361a: arp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arp_invalidate(struct net_device *dev, __be32 ip, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81eeaaf0)
Location: net/ipv4/arp.c:1140
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81eeaaf0-ffffffff81eeac1a: arp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arp_invalidate(struct net_device *dev, __be32 ip, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f4a450)
Location: net/ipv4/arp.c:1140
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81f4a450-ffffffff81f4a575: arp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arp_invalidate(struct net_device *dev, __be32 ip, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff82010560)
Location: net/ipv4/arp.c:1141
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff82010560-ffffffff82010685: arp_invalidate (STB_GLOBAL)
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
In net/ipv4/arp.c (ffff800010ca1e3c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (c0daec68)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (c000000000db5144)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffe0007fdaea)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff8198c16c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81945c2c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff819f697c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
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
In net/ipv4/arp.c (ffffffff81a00b9c)
Location: net/ipv4/arp.c:1113
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
