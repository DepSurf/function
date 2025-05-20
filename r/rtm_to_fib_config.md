# Function: <code>rtm_to_fib_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81799ce0)
Location: net/ipv4/fib_frontend.c:634
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
```
**Symbols:**

```
ffffffff81799ce0-ffffffff81799e7a: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818079c0)
Location: net/ipv4/fib_frontend.c:634
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff818079c0-ffffffff81807b78: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81838a60)
Location: net/ipv4/fib_frontend.c:627
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81838a60-ffffffff81838c38: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81859d20)
Location: net/ipv4/fib_frontend.c:630
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81859d20-ffffffff81859f35: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818d9c20)
Location: net/ipv4/fib_frontend.c:652
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff818d9c20-ffffffff818d9e3b: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819306b0)
Location: net/ipv4/fib_frontend.c:657
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff819306b0-ffffffff819308d5: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8195fac0)
Location: net/ipv4/fib_frontend.c:667
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff8195fac0-ffffffff8195fd54: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c6420)
Location: net/ipv4/fib_frontend.c:726
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff819c6420-ffffffff819c679d: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fcfd0)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff819fcfd0-ffffffff819fd34d: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeb9f0)
Location: net/ipv4/fib_frontend.c:719
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81aeb9f0-ffffffff81aebd56: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af8900)
Location: net/ipv4/fib_frontend.c:719
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81af8900-ffffffff81af8c55: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae4060)
Location: net/ipv4/fib_frontend.c:721
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81ae4060-ffffffff81ae43f1: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba39b0)
Location: net/ipv4/fib_frontend.c:721
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81ba39b0-ffffffff81ba3d41: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d36220)
Location: net/ipv4/fib_frontend.c:724
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81d36220-ffffffff81d365e4: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efe850)
Location: net/ipv4/fib_frontend.c:724
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81efe850-ffffffff81efec26: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5e2e0)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81f5e2e0-ffffffff81f5e6b6: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff820248a0)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff820248a0-ffffffff82024c85: rtm_to_fib_config (STB_LOCAL)
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
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb5150)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffff800010cb5150-ffff800010cb54f8: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc0ad4)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
c0dc0ad4-c0dc0e6c: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dccae0)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
c000000000dccae0-c000000000dccf68: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080cbe4)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffe00080cbe4-ffffffe00080ce80: rtm_to_fib_config (STB_LOCAL)
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
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199cd70)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff8199cd70-ffffffff8199d0ed: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81956830)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81956830-ffffffff81956bad: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a07610)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81a07610-ffffffff81a0798d: rtm_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtm_to_fib_config(struct net *net, struct sk_buff *skb, struct nlmsghdr *nlh, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a11d50)
Location: net/ipv4/fib_frontend.c:727
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
```
**Symbols:**

```
ffffffff81a11d50-ffffffff81a120cd: rtm_to_fib_config (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
