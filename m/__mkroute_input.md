# Function: <code>__mkroute_input</code>

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
In net/ipv4/route.c (ffffffff817559e6)
Location: net/ipv4/route.c:1591
Inline: True
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
In net/ipv4/route.c (ffffffff817c1b92)
Location: net/ipv4/route.c:1598
Inline: True
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
In net/ipv4/route.c (ffffffff817f218a)
Location: net/ipv4/route.c:1621
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
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
In net/ipv4/route.c (ffffffff81811d25)
Location: net/ipv4/route.c:1654
Inline: True
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
In net/ipv4/route.c (ffffffff81891374)
Location: net/ipv4/route.c:1667
Inline: True
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
In net/ipv4/route.c (ffffffff818e4d7e)
Location: net/ipv4/route.c:1697
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff81911c9a)
Location: net/ipv4/route.c:1694
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff819743c6)
Location: net/ipv4/route.c:1779
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff819aade6)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1785
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a94040-ffffffff81a94349: __mkroute_input (STB_LOCAL)
ffffffff81a971b5-ffffffff81a971cb: __mkroute_input.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1791
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a9df90-ffffffff81a9e308: __mkroute_input (STB_LOCAL)
ffffffff81c3248d-ffffffff81c324a3: __mkroute_input.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1779
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81a88ee0-ffffffff81a89262: __mkroute_input (STB_LOCAL)
ffffffff81c24776-ffffffff81c2478c: __mkroute_input.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1775
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81b43650-ffffffff81b439e6: __mkroute_input (STB_LOCAL)
ffffffff81d39e3f-ffffffff81d39e55: __mkroute_input.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1794
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81cd0140-ffffffff81cd04d5: __mkroute_input (STB_LOCAL)
ffffffff81f06586-ffffffff81f06597: __mkroute_input.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e902e0)
Location: net/ipv4/route.c:1790
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81e902e0-ffffffff81e90675: __mkroute_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeea50)
Location: net/ipv4/route.c:1788
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81eeea50-ffffffff81eeee0e: __mkroute_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mkroute_input(struct sk_buff *skb, const struct fib_result *res, struct in_device *in_dev, __be32 daddr, __be32 saddr, u32 tos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb2bb0)
Location: net/ipv4/route.c:1790
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81fb2bb0-ffffffff81fb2f6e: __mkroute_input (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5b0a8)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (c0d6a5f0)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (c000000000d5ce80)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffe0007c444a)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff8194ac56)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff81904746)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff819b5426)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
In net/ipv4/route.c (ffffffff819bef28)
Location: net/ipv4/route.c:1783
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
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
