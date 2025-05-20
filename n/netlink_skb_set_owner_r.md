# Function: <code>netlink_skb_set_owner_r</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174a3c0)
Location: net/netlink/af_netlink.c:918
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8174a3c0-ffffffff8174a42a: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b72e0)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff817b72e0-ffffffff817b734a: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e6d80)
Location: net/netlink/af_netlink.c:316
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff817e6d80-ffffffff817e6dea: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81806740)
Location: net/netlink/af_netlink.c:347
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81806740-ffffffff81806789: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885410)
Location: net/netlink/af_netlink.c:349
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81885410-ffffffff81885459: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d8c30)
Location: net/netlink/af_netlink.c:383
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff818d8c30-ffffffff818d8c79: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81905420)
Location: net/netlink/af_netlink.c:383
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81905420-ffffffff81905469: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81966830-ffffffff81966886: netlink_skb_set_owner_r (STB_LOCAL)
ffffffff8196b05a-ffffffff8196b075: netlink_skb_set_owner_r.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d230)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff8199d230-ffffffff8199d279: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76470)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81a76470-ffffffff81a764b9: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7f1e0)
Location: net/netlink/af_netlink.c:375
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81a7f1e0-ffffffff81a7f229: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a681c0)
Location: net/netlink/af_netlink.c:383
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81a681c0-ffffffff81a68209: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b216e0)
Location: net/netlink/af_netlink.c:383
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81b216e0-ffffffff81b21729: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ca9ca0)
Location: net/netlink/af_netlink.c:387
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81ca9ca0-ffffffff81ca9cf5: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e66ca0)
Location: net/netlink/af_netlink.c:387
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81e66ca0-ffffffff81e66cf5: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec2a60)
Location: net/netlink/af_netlink.c:387
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81ec2a60-ffffffff81ec2ab5: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f85db0)
Location: net/netlink/af_netlink.c:385
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff81f85db0-ffffffff81f85e0d: netlink_skb_set_owner_r (STB_LOCAL)
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
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4b8d0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffff800010c4b8d0-ffff800010c4b954: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5b634)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
c0d5b634-c0d5b6c8: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48b00)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
c000000000d48b00-c000000000d48b6c: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b7bd0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffe0007b7bd0-ffffffe0007b7c30: netlink_skb_set_owner_r (STB_LOCAL)
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
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d0a0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff8193d0a0-ffffffff8193d0e9: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f6ba0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff818f6ba0-ffffffff818f6be9: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e230)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff8198e230-ffffffff8198e279: netlink_skb_set_owner_r (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_skb_set_owner_r(struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b0ad0)
Location: net/netlink/af_netlink.c:374
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff819b0ad0-ffffffff819b0b19: netlink_skb_set_owner_r (STB_LOCAL)
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
