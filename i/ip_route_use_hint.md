# Function: <code>ip_route_use_hint</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a95730)
Location: net/ipv4/route.c:2030
Inline: False
```
**Symbols:**

```
ffffffff81a95730-ffffffff81a95866: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9f7c0)
Location: net/ipv4/route.c:2036
Inline: False
```
**Symbols:**

```
ffffffff81a9f7c0-ffffffff81a9f8f6: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8a700)
Location: net/ipv4/route.c:2024
Inline: False
```
**Symbols:**

```
ffffffff81a8a700-ffffffff81a8a836: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b455c0)
Location: net/ipv4/route.c:2143
Inline: False
```
**Symbols:**

```
ffffffff81b455c0-ffffffff81b45726: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd22e0)
Location: net/ipv4/route.c:2165
Inline: False
```
**Symbols:**

```
ffffffff81cd22e0-ffffffff81cd2465: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e92910)
Location: net/ipv4/route.c:2160
Inline: False
```
**Symbols:**

```
ffffffff81e92910-ffffffff81e92a95: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef10b0)
Location: net/ipv4/route.c:2158
Inline: False
```
**Symbols:**

```
ffffffff81ef10b0-ffffffff81ef1236: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_route_use_hint(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, const struct sk_buff *hint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb5200)
Location: net/ipv4/route.c:2161
Inline: False
```
**Symbols:**

```
ffffffff81fb5200-ffffffff81fb5386: ip_route_use_hint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
