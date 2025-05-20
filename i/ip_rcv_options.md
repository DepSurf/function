# Function: <code>ip_rcv_options</code>

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
In net/ipv4/ip_input.c (ffffffff81758861)
Location: net/ipv4/ip_input.c:262
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff817c4b9a)
Location: net/ipv4/ip_input.c:262
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff817f46ba)
Location: net/ipv4/ip_input.c:262
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff81814afc)
Location: net/ipv4/ip_input.c:262
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff81893cb0)
Location: net/ipv4/ip_input.c:262
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff818e7f5b)
Location: net/ipv4/ip_input.c:261
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
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
In net/ipv4/ip_input.c (ffffffff81914e15)
Location: net/ipv4/ip_input.c:260
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819772ea)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819adc7a)
Location: net/ipv4/ip_input.c:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:257
Inline: False
```
**Symbols:**

```
ffffffff81a97930-ffffffff81a97a61: ip_rcv_options (STB_LOCAL)
ffffffff81a98938-ffffffff81a98956: ip_rcv_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:257
Inline: False
```
**Symbols:**

```
ffffffff81aa1890-ffffffff81aa19c1: ip_rcv_options (STB_LOCAL)
ffffffff81c32532-ffffffff81c32550: ip_rcv_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:258
Inline: False
```
**Symbols:**

```
ffffffff81a8c860-ffffffff81a8c992: ip_rcv_options (STB_LOCAL)
ffffffff81c2481d-ffffffff81c2483b: ip_rcv_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:258
Inline: False
```
**Symbols:**

```
ffffffff81b47990-ffffffff81b47ac2: ip_rcv_options (STB_LOCAL)
ffffffff81d3a045-ffffffff81d3a063: ip_rcv_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:260
Inline: False
```
**Symbols:**

```
ffffffff81cd4bf0-ffffffff81cd4d24: ip_rcv_options (STB_LOCAL)
ffffffff81f067da-ffffffff81f067f3: ip_rcv_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e94f20)
Location: net/ipv4/ip_input.c:260
Inline: False
```
**Symbols:**

```
ffffffff81e94f20-ffffffff81e95068: ip_rcv_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef36f0)
Location: net/ipv4/ip_input.c:260
Inline: False
```
**Symbols:**

```
ffffffff81ef36f0-ffffffff81ef3838: ip_rcv_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ip_rcv_options(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb7680)
Location: net/ipv4/ip_input.c:260
Inline: False
```
**Symbols:**

```
ffffffff81fb7680-ffffffff81fb77c8: ip_rcv_options (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffff800010c5e400)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (c0d6d454)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (c000000000d607e0)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffe0007c689e)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffff8194daea)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819075da)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819b82ba)
Location: net/ipv4/ip_input.c:257
Inline: True
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
In net/ipv4/ip_input.c (ffffffff819c1b1a)
Location: net/ipv4/ip_input.c:257
Inline: True
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
