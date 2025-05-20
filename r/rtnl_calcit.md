# Function: <code>rtnl_calcit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 rtnl_calcit(struct sk_buff *skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172b8f0)
Location: net/core/rtnetlink.c:2455
Inline: False
```
**Symbols:**

```
ffffffff8172b8f0-ffffffff8172b9e1: rtnl_calcit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 rtnl_calcit(struct sk_buff *skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817951a0)
Location: net/core/rtnetlink.c:2649
Inline: False
```
**Symbols:**

```
ffffffff817951a0-ffffffff8179529c: rtnl_calcit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 rtnl_calcit(struct sk_buff *skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c2a10)
Location: net/core/rtnetlink.c:2722
Inline: False
```
**Symbols:**

```
ffffffff817c2a10-ffffffff817c2b1d: rtnl_calcit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 rtnl_calcit(struct sk_buff *skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e11c0)
Location: net/core/rtnetlink.c:2810
Inline: False
```
**Symbols:**

```
ffffffff817e11c0-ffffffff817e12d0: rtnl_calcit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185b920)
Location: net/core/rtnetlink.c:3027
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff8185b920-ffffffff8185ba2c: rtnl_calcit.isra.28 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818a72c0)
Location: net/core/rtnetlink.c:3174
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff818a72c0-ffffffff818a73be: rtnl_calcit.isra.33 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818cb100)
Location: net/core/rtnetlink.c:3315
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff818cb100-ffffffff818cb1fe: rtnl_calcit.isra.31 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81917b40)
Location: net/core/rtnetlink.c:3376
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81917b40-ffffffff81917c3e: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff8194a160)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff8194a160-ffffffff8194a25e: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1a770)
Location: net/core/rtnetlink.c:3610
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81a1a770-ffffffff81a1a870: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1a980)
Location: net/core/rtnetlink.c:3703
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81a1a980-ffffffff81a1aa8d: rtnl_calcit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a018a0)
Location: net/core/rtnetlink.c:3701
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81a018a0-ffffffff81a019cb: rtnl_calcit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab3ca0)
Location: net/core/rtnetlink.c:3722
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81ab3ca0-ffffffff81ab3dcb: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81c2d350)
Location: net/core/rtnetlink.c:3814
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81c2d350-ffffffff81c2d49a: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81de04d0)
Location: net/core/rtnetlink.c:3858
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81de04d0-ffffffff81de061a: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81e51c60)
Location: net/core/rtnetlink.c:3940
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81e51c60-ffffffff81e51daa: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81f10d30)
Location: net/core/rtnetlink.c:3980
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff81f10d30-ffffffff81f10e83: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffff800010bec380)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffff800010bec380-ffff800010bec4b4: rtnl_calcit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 rtnl_calcit(struct sk_buff *skb, struct nlmsghdr *nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d04a9c)
Location: net/core/rtnetlink.c:3407
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
c0d04a9c-c0d04bc4: rtnl_calcit (STB_LOCAL)
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
In net/core/rtnetlink.c (c000000000ccf450)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
c000000000ccf450-c000000000ccf5f4: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffe00076fd6c)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffe00076fd6c-ffffffe00076fe5a: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818ea130)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff818ea130-ffffffff818ea22e: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff818a3f70)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff818a3f70-ffffffff818a406e: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff8193b160)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff8193b160-ffffffff8193b25e: rtnl_calcit.isra.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff8195c9a0)
Location: net/core/rtnetlink.c:3407
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
```
**Symbols:**

```
ffffffff8195c9a0-ffffffff8195caae: rtnl_calcit.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
