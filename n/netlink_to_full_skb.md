# Function: <code>netlink_to_full_skb</code>

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
Location: net/netlink/af_netlink.c:128
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
In net/netlink/af_netlink.c (ffffffff817b7d3b)
Location: net/netlink/af_netlink.c:128
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
In net/netlink/af_netlink.c (ffffffff817e781b)
Location: net/netlink/af_netlink.c:128
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
In net/netlink/af_netlink.c (ffffffff8180752a)
Location: net/netlink/af_netlink.c:159
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
In net/netlink/af_netlink.c (ffffffff8188606b)
Location: net/netlink/af_netlink.c:158
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
In net/netlink/af_netlink.c (ffffffff818d9a0d)
Location: net/netlink/af_netlink.c:158
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
In net/netlink/af_netlink.c (ffffffff81906460)
Location: net/netlink/af_netlink.c:158
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
In net/netlink/af_netlink.c (ffffffff8196767c)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffff8199e10c)
Location: net/netlink/af_netlink.c:154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76ce0)
Location: net/netlink/af_netlink.c:154
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
**Symbols:**

```
ffffffff81a76ce0-ffffffff81a76d63: netlink_to_full_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7fa60)
Location: net/netlink/af_netlink.c:155
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
**Symbols:**

```
ffffffff81a7fa60-ffffffff81a7fae3: netlink_to_full_skb.constprop.0 (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81a68ab8)
Location: net/netlink/af_netlink.c:163
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
In net/netlink/af_netlink.c (ffffffff81b2204c)
Location: net/netlink/af_netlink.c:163
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
In net/netlink/af_netlink.c (ffffffff81caacbc)
Location: net/netlink/af_netlink.c:167
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e67d20)
Location: net/netlink/af_netlink.c:167
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
**Symbols:**

```
ffffffff81e67d20-ffffffff81e67dac: netlink_to_full_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec3b80)
Location: net/netlink/af_netlink.c:167
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
**Symbols:**

```
ffffffff81ec3b80-ffffffff81ec3c0c: netlink_to_full_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f86f40)
Location: net/netlink/af_netlink.c:167
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
**Symbols:**

```
ffffffff81f86f40-ffffffff81f86fc9: netlink_to_full_skb.constprop.0 (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffff800010c4b634)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (c0d5c0a4)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (c000000000d49858)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffe0007b8d62)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffff8193df7c)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffff818f7a7c)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffff8198f10c)
Location: net/netlink/af_netlink.c:154
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
In net/netlink/af_netlink.c (ffffffff819b19f4)
Location: net/netlink/af_netlink.c:154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
</ul>

## Differences
