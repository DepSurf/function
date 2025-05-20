# Function: <code>__netlink_deliver_tap_skb</code>

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
In net/netlink/af_netlink.c (ffffffff8174b204)
Location: net/netlink/af_netlink.c:219
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff817b7d1e)
Location: net/netlink/af_netlink.c:219
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff817e77fe)
Location: net/netlink/af_netlink.c:219
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff8180750d)
Location: net/netlink/af_netlink.c:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81886026)
Location: net/netlink/af_netlink.c:249
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff818d9932)
Location: net/netlink/af_netlink.c:281
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81906382)
Location: net/netlink/af_netlink.c:281
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81967627)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff8199e0b7)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __netlink_deliver_tap_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76d70)
Location: net/netlink/af_netlink.c:272
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
**Symbols:**

```
ffffffff81a76d70-ffffffff81a76e5d: __netlink_deliver_tap_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __netlink_deliver_tap_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7faf0)
Location: net/netlink/af_netlink.c:273
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
**Symbols:**

```
ffffffff81a7faf0-ffffffff81a7fbdd: __netlink_deliver_tap_skb (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81a68a8d)
Location: net/netlink/af_netlink.c:281
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81b2201c)
Location: net/netlink/af_netlink.c:281
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81caac8a)
Location: net/netlink/af_netlink.c:285
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81e67e30)
Location: net/netlink/af_netlink.c:285
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81ec3c88)
Location: net/netlink/af_netlink.c:285
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff81f87048)
Location: net/netlink/af_netlink.c:285
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffff800010c4b5f4)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (c0d5c000)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (c000000000d497f8)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffe0007b8cfc)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff8193df27)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff818f7a27)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff8198f0b7)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
In net/netlink/af_netlink.c (ffffffff819b199f)
Location: net/netlink/af_netlink.c:272
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
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
