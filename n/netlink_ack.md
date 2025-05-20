# Function: <code>netlink_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174ec50)
Location: net/netlink/af_netlink.c:2950
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff8174ec50-ffffffff8174ed78: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817bac20)
Location: net/netlink/af_netlink.c:2219
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff817bac20-ffffffff817bad45: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ea5c0)
Location: net/netlink/af_netlink.c:2237
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff817ea5c0-ffffffff817ea6e5: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8180a2a0)
Location: net/netlink/af_netlink.c:2288
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff8180a2a0-ffffffff8180a5d4: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81889220)
Location: net/netlink/af_netlink.c:2312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81889220-ffffffff81889508: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dcca0)
Location: net/netlink/af_netlink.c:2353
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff818dcca0-ffffffff818dcf98: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81909670)
Location: net/netlink/af_netlink.c:2375
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81909670-ffffffff81909965: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (0)
Location: net/netlink/af_netlink.c:2375
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff8196b134-ffffffff8196b1a0: netlink_ack.cold (STB_LOCAL)
ffffffff8196a980-ffffffff8196ac6b: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a1410)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff819a1410-ffffffff819a1706: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7adb0)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81a7adb0-ffffffff81a7b0c9: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a83c00)
Location: net/netlink/af_netlink.c:2396
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81a83c00-ffffffff81a83f5f: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6cd20)
Location: net/netlink/af_netlink.c:2406
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81a6cd20-ffffffff81a6d092: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b263a0)
Location: net/netlink/af_netlink.c:2417
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81b263a0-ffffffff81b2670b: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caefd0)
Location: net/netlink/af_netlink.c:2403
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81caefd0-ffffffff81caf3f2: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6c630)
Location: net/netlink/af_netlink.c:2487
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81e6c630-ffffffff81e6c9f0: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec8690)
Location: net/netlink/af_netlink.c:2462
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81ec8690-ffffffff81ec8a50: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8ba30)
Location: net/netlink/af_netlink.c:2456
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - kernel/audit.c:auditd_set
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81f8ba30-ffffffff81f8bcce: netlink_ack (STB_GLOBAL)
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
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4fa80)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffff800010c4fa80-ffff800010c4fd48: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5fc5c)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
c0d5fc5c-c0d5ff60: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4e500)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
c000000000d4e500-c000000000d4e8dc: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007bb66a)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffe0007bb66a-ffffffe0007bb89c: netlink_ack (STB_GLOBAL)
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
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81941280)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff81941280-ffffffff81941576: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fad70)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff818fad70-ffffffff818fb066: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81992410)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
  - net/netfilter/nfnetlink.c:nfnetlink_rcv
  - net/netfilter/nfnetlink.c:nfnetlink_rcv
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
```
**Symbols:**

```
ffffffff81992410-ffffffff81992706: netlink_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_ack(struct sk_buff *in_skb, struct nlmsghdr *nlh, int err, const struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b4f00)
Location: net/netlink/af_netlink.c:2376
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - drivers/scsi/scsi_netlink.c:scsi_nl_rcv_msg
  - net/netlink/af_netlink.c:netlink_rcv_skb
```
**Symbols:**

```
ffffffff819b4f00-ffffffff819b51f6: netlink_ack (STB_GLOBAL)
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
<code>const struct netlink_ext_ack *extack</code>
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
