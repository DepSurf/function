# Function: <code>tun_build_skb</code>

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
In drivers/net/tun.c (ffffffff816fee30)
Location: drivers/net/tun.c:1431
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8173ce60)
Location: drivers/net/tun.c:1619
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8173ce60-ffffffff8173d308: tun_build_skb.isra.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81760a90)
Location: drivers/net/tun.c:1662
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81760a90-ffffffff81760d8c: tun_build_skb.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8179e280)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8179e280-ffffffff8179e60d: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817c1d10)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817c1d10-ffffffff817c209d: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tun_build_skb(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *from, struct virtio_net_hdr *hdr, int len, int *skb_xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188cc80)
Location: drivers/net/tun.c:1620
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8188cc80-ffffffff8188d037: tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tun_build_skb(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *from, struct virtio_net_hdr *hdr, int len, int *skb_xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189aee0)
Location: drivers/net/tun.c:1551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8189aee0-ffffffff8189b2a3: tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tun_build_skb(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *from, struct virtio_net_hdr *hdr, int len, int *skb_xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187d750)
Location: drivers/net/tun.c:1562
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8187d750-ffffffff8187db00: tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tun_build_skb(struct tun_struct *tun, struct tun_file *tfile, struct iov_iter *from, struct virtio_net_hdr *hdr, int len, int *skb_xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190edc0)
Location: drivers/net/tun.c:1618
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8190edc0-ffffffff8190f1c6: tun_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81a662a0)
Location: drivers/net/tun.c:1646
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81a662a0-ffffffff81a666e4: tun_build_skb.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81bf1740)
Location: drivers/net/tun.c:1649
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81bf1740-ffffffff81bf1bae: tun_build_skb.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81c4a3d0)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81c4a3d0-ffffffff81c4a81e: tun_build_skb.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81cffd50)
Location: drivers/net/tun.c:1664
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81cffd50-ffffffff81d0019a: tun_build_skb.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffff8000109df208)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffff8000109df208-ffff8000109df53c: tun_build_skb.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (c0ac48c8)
Location: drivers/net/tun.c:1655
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (c000000000a9e930)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c000000000a9e930-c000000000a9ee04: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffe000627754)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffe000627754-ffffffe000627a30: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817867e0)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817867e0-ffffffff81786b6d: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81766130)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81766130-ffffffff817664bd: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817b6b90)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817b6b90-ffffffff817b6f1d: tun_build_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817d0db0)
Location: drivers/net/tun.c:1655
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817d0db0-ffffffff817d116c: tun_build_skb.isra.0 (STB_LOCAL)
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
</ul>
