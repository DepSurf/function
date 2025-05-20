# Function: <code>selinux_netlink_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81345420)
Location: security/selinux/hooks.c:5143
Inline: False
```
**Symbols:**

```
ffffffff81345420-ffffffff81345519: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137acc0)
Location: security/selinux/hooks.c:5287
Inline: False
```
**Symbols:**

```
ffffffff8137acc0-ffffffff8137add8: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81391110)
Location: security/selinux/hooks.c:5368
Inline: False
```
**Symbols:**

```
ffffffff81391110-ffffffff81391228: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a7860)
Location: security/selinux/hooks.c:5346
Inline: False
```
**Symbols:**

```
ffffffff813a7860-ffffffff813a7974: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cd030)
Location: security/selinux/hooks.c:5361
Inline: False
```
**Symbols:**

```
ffffffff813cd030-ffffffff813cd144: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5903
Inline: False
```
**Symbols:**

```
ffffffff813fac20-ffffffff813facf9: selinux_netlink_send (STB_LOCAL)
ffffffff81402a93-ffffffff81402ae1: selinux_netlink_send.cold.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5624
Inline: False
```
**Symbols:**

```
ffffffff81417200-ffffffff814172df: selinux_netlink_send (STB_LOCAL)
ffffffff8141e66c-ffffffff8141e6ba: selinux_netlink_send.cold.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5823
Inline: False
```
**Symbols:**

```
ffffffff81444dd0-ffffffff81444eb2: selinux_netlink_send (STB_LOCAL)
ffffffff8144c25c-ffffffff8144c2ab: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffff8145e940-ffffffff8145ea22: selinux_netlink_send (STB_LOCAL)
ffffffff8146604c-ffffffff8146609b: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5836
Inline: False
```
**Symbols:**

```
ffffffff814b1a20-ffffffff814b1b8d: selinux_netlink_send (STB_LOCAL)
ffffffff814b9d34-ffffffff814b9d70: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5852
Inline: False
```
**Symbols:**

```
ffffffff814cee10-ffffffff814cef7d: selinux_netlink_send (STB_LOCAL)
ffffffff81bf01de-ffffffff81bf021a: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:6016
Inline: False
```
**Symbols:**

```
ffffffff814d5610-ffffffff814d577d: selinux_netlink_send (STB_LOCAL)
ffffffff81be225d-ffffffff81be2299: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:6001
Inline: False
```
**Symbols:**

```
ffffffff8152e250-ffffffff8152e3c5: selinux_netlink_send (STB_LOCAL)
ffffffff81cd361d-ffffffff81cd3674: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5900
Inline: False
```
**Symbols:**

```
ffffffff815c4e60-ffffffff815c4fd4: selinux_netlink_send (STB_LOCAL)
ffffffff81e86732-ffffffff81e86798: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5915
Inline: False
```
**Symbols:**

```
ffffffff81671990-ffffffff81671b58: selinux_netlink_send (STB_LOCAL)
ffffffff820732c2-ffffffff820732dd: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5868
Inline: False
```
**Symbols:**

```
ffffffff816aa170-ffffffff816aa32d: selinux_netlink_send (STB_LOCAL)
ffffffff820f2f05-ffffffff820f2f20: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5953
Inline: False
```
**Symbols:**

```
ffffffff816e6f70-ffffffff816e712d: selinux_netlink_send (STB_LOCAL)
ffffffff821d018a-ffffffff821d01a5: selinux_netlink_send.cold (STB_LOCAL)
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
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054ba40)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffff80001054ba40-ffff80001054bba0: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0701d90)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
c0701d90-c0701ef0: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a3f40)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
c0000000006a3f40-c0000000006a4104: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a63d2)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffe0003a63d2-ffffffe0003a64cc: selinux_netlink_send (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffff81456f20-ffffffff81457002: selinux_netlink_send (STB_LOCAL)
ffffffff8145e62c-ffffffff8145e67b: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffff81447960-ffffffff81447a42: selinux_netlink_send (STB_LOCAL)
ffffffff8144f05c-ffffffff8144f0ab: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffff81452fc0-ffffffff814530a2: selinux_netlink_send (STB_LOCAL)
ffffffff8145a6cc-ffffffff8145a71b: selinux_netlink_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_netlink_send(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5881
Inline: False
```
**Symbols:**

```
ffffffff8146aac0-ffffffff8146aba2: selinux_netlink_send (STB_LOCAL)
ffffffff81471e6c-ffffffff81471ebb: selinux_netlink_send.cold (STB_LOCAL)
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
