# Function: <code>netlink_deliver_tap</code>

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
In net/netlink/af_netlink.c (ffffffff8174b39c)
Location: net/netlink/af_netlink.c:262
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff817ba7c0)
Location: net/netlink/af_netlink.c:262
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff817ea160)
Location: net/netlink/af_netlink.c:262
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81809e32)
Location: net/netlink/af_netlink.c:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81888d98)
Location: net/netlink/af_netlink.c:295
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff818dc7e5)
Location: net/netlink/af_netlink.c:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff819091c2)
Location: net/netlink/af_netlink.c:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819675a0)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff819675a0-ffffffff819677b3: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199e030)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff8199e030-ffffffff8199e243: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76e60)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a76e60-ffffffff81a76ede: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7fbe0)
Location: net/netlink/af_netlink.c:319
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a7fbe0-ffffffff81a7fc6a: netlink_deliver_tap (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81a6c7d3)
Location: net/netlink/af_netlink.c:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81b25e23)
Location: net/netlink/af_netlink.c:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81cae9f6)
Location: net/netlink/af_netlink.c:331
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81e6c036)
Location: net/netlink/af_netlink.c:331
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81ec8096)
Location: net/netlink/af_netlink.c:331
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
In net/netlink/af_netlink.c (ffffffff81f8b4ac)
Location: net/netlink/af_netlink.c:331
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
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
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4b528)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffff800010c4b528-ffff800010c4b744: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5bf24)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
c0d5bf24-c0d5c168: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d496e0)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
c000000000d496e0-c000000000d499e4: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b8c68)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffe0007b8c68-ffffffe0007b8e46: netlink_deliver_tap (STB_LOCAL)
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
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193dea0)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff8193dea0-ffffffff8193e0b3: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f79a0)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff818f79a0-ffffffff818f7bb3: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198f030)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff8198f030-ffffffff8198f243: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_deliver_tap(struct net *net, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b1900)
Location: net/netlink/af_netlink.c:318
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff819b1900-ffffffff819b1b2b: netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
