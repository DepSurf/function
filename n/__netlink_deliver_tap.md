# Function: <code>__netlink_deliver_tap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174b1a0)
Location: net/netlink/af_netlink.c:247
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8174b1a0-ffffffff8174b376: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b7cc0)
Location: net/netlink/af_netlink.c:247
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff817b7cc0-ffffffff817b7e8e: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e77a0)
Location: net/netlink/af_netlink.c:247
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff817e77a0-ffffffff817e796e: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818074b0)
Location: net/netlink/af_netlink.c:278
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff818074b0-ffffffff81807672: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885fb0)
Location: net/netlink/af_netlink.c:280
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81885fb0-ffffffff8188619d: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d98c0)
Location: net/netlink/af_netlink.c:312
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff818d98c0-ffffffff818d9aa7: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81906310)
Location: net/netlink/af_netlink.c:312
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81906310-ffffffff819064fa: __netlink_deliver_tap (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff819675e5)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffff8199e075)
Location: net/netlink/af_netlink.c:303
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76e95)
Location: net/netlink/af_netlink.c:303
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7fc1c)
Location: net/netlink/af_netlink.c:304
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a68a20)
Location: net/netlink/af_netlink.c:312
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81a68a20-ffffffff81a68bec: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b21fb0)
Location: net/netlink/af_netlink.c:312
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81b21fb0-ffffffff81b22199: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caac10)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81caac10-ffffffff81caae08: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e67dc0)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81e67dc0-ffffffff81e67f4c: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec3c20)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81ec3c20-ffffffff81ec3db2: __netlink_deliver_tap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __netlink_deliver_tap(struct sk_buff *skb, struct netlink_tap_net *nn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f86fe0)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff81f86fe0-ffffffff81f87172: __netlink_deliver_tap (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffff800010c4b570)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (c0d5bf68)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (c000000000d4973c)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffe0007b8cd0)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffff8193dee5)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffff818f79e5)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffff8198f075)
Location: net/netlink/af_netlink.c:303
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
In net/netlink/af_netlink.c (ffffffff819b1958)
Location: net/netlink/af_netlink.c:303
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_tap_net *nn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
