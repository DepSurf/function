# Function: <code>rtnl_link_fill</code>

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
In net/core/rtnetlink.c (ffffffff8172e74c)
Location: net/core/rtnetlink.c:594
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff81798115)
Location: net/core/rtnetlink.c:616
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff817c5e99)
Location: net/core/rtnetlink.c:617
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff817e478f)
Location: net/core/rtnetlink.c:619
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8185f8b3)
Location: net/core/rtnetlink.c:592
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818ab93a)
Location: net/core/rtnetlink.c:675
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818cf61d)
Location: net/core/rtnetlink.c:685
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8191c373)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8194e99c)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1dc60)
Location: net/core/rtnetlink.c:680
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a1dc60-ffffffff81a1ddfd: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1df90)
Location: net/core/rtnetlink.c:682
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a1df90-ffffffff81a1e12d: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a05b00)
Location: net/core/rtnetlink.c:684
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81a05b00-ffffffff81a05d74: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab7f40)
Location: net/core/rtnetlink.c:684
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81ab7f40-ffffffff81ab81b4: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c31b90)
Location: net/core/rtnetlink.c:721
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81c31b90-ffffffff81c31e05: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de4f50)
Location: net/core/rtnetlink.c:722
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81de4f50-ffffffff81de51c5: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e56970)
Location: net/core/rtnetlink.c:725
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81e56970-ffffffff81e56be5: rtnl_link_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_link_fill(struct sk_buff *skb, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f15cc0)
Location: net/core/rtnetlink.c:720
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81f15cc0-ffffffff81f15f35: rtnl_link_fill (STB_LOCAL)
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
In net/core/rtnetlink.c (ffff800010bf07e4)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (c0d08eec)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (c000000000cd4db0)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffe0007726fc)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818ee96c)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff818a87ac)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8193f99c)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In net/core/rtnetlink.c (ffffffff8196127f)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
