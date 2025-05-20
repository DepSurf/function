# Function: <code>zerocopy_sg_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170d550)
Location: net/core/datagram.c:525
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8170d550-ffffffff8170d739: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81774ba0)
Location: net/core/datagram.c:547
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81774ba0-ffffffff81774d89: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1ea0)
Location: net/core/datagram.c:567
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817a1ea0-ffffffff817a2089: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (ffffffff817bff70)
Location: net/core/datagram.c:592
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff817bff70-ffffffff817c0117: zerocopy_sg_from_iter.part.10 (STB_LOCAL)
ffffffff817c04c0-ffffffff817c050c: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839ee0)
Location: net/core/datagram.c:638
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81839ee0-ffffffff81839f33: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884610)
Location: net/core/datagram.c:636
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81884610-ffffffff81884663: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4580)
Location: net/core/datagram.c:671
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff818a4580-ffffffff818a45cd: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818efbc0)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff818efbc0-ffffffff818efc0f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81921be0)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81921be0-ffffffff81921c2f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f5520)
Location: net/core/datagram.c:674
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff819f5520-ffffffff819f556f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4fe0)
Location: net/core/datagram.c:699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff819f4fe0-ffffffff819f502f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819db170)
Location: net/core/datagram.c:699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff819db170-ffffffff819db1be: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8b8f0)
Location: net/core/datagram.c:699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81a8b8f0-ffffffff81a8b93e: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c00ff0)
Location: net/core/datagram.c:697
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81c00ff0-ffffffff81c01048: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81db0390)
Location: net/core/datagram.c:699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81db0390-ffffffff81db03ee: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e20840)
Location: net/core/datagram.c:707
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81e20840-ffffffff81e2089e: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81ede710)
Location: net/core/datagram.c:726
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81ede710-ffffffff81ede76e: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbc240)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffff800010bbc240-ffff800010bbc2ac: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd86b4)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c0cd86b4-c0cd8718: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c954d0)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c000000000c954d0-c000000000c9557c: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074afba)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffe00074afba-ffffffe00074b01e: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c1be0)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff818c1be0-ffffffff818c1c2f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187bb20)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff8187bb20-ffffffff8187bb6f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81912be0)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81912be0-ffffffff81912c2f: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int zerocopy_sg_from_iter(struct sk_buff *skb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933d60)
Location: net/core/datagram.c:670
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81933d60-ffffffff81933daf: zerocopy_sg_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
