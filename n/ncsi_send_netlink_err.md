# Function: <code>ncsi_send_netlink_err</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a04200)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a04200-ffffffff81a042e9: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a734a0)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a734a0-ffffffff81a73592: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81aa9c90)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81aa9c90-ffffffff81aa9d82: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5e90)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81ba5e90-ffffffff81ba5f82: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81bb5370)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81bb5370-ffffffff81bb5462: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81ba4370)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81ba4370-ffffffff81ba445f: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81c71f00)
Location: net/ncsi/ncsi-netlink.c:563
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81c71f00-ffffffff81c71fef: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81e15a90)
Location: net/ncsi/ncsi-netlink.c:563
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81e15a90-ffffffff81e15b7f: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81feca40)
Location: net/ncsi/ncsi-netlink.c:563
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81feca40-ffffffff81fecb2f: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff82068ce0)
Location: net/ncsi/ncsi-netlink.c:563
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff82068ce0-ffffffff82068dcf: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, const struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff8213bf60)
Location: net/ncsi/ncsi-netlink.c:563
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff8213bf60-ffffffff8213c04f: ncsi_send_netlink_err (STB_GLOBAL)
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
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffff800010d7d960)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffff800010d7d960-ffff800010d7da40: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c0e784a0)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c0e784a0-c0e78588: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c000000000ebd480)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
c000000000ebd480-c000000000ebd5b0: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab190)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffe0008ab190-ffffffe0008ab262: ncsi_send_netlink_err (STB_GLOBAL)
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
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a49020)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a49020-ffffffff81a49112: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a05c10)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81a05c10-ffffffff81a05d02: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4ed0)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81ab4ed0-ffffffff81ab4fc2: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ncsi_send_netlink_err(struct net_device *dev, u32 snd_seq, u32 snd_portid, struct nlmsghdr *nlhdr, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81ac1270)
Location: net/ncsi/ncsi-netlink.c:559
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
```
**Symbols:**

```
ffffffff81ac1270-ffffffff81ac1362: ncsi_send_netlink_err (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nlmsghdr *nlhdr</code> ➡️ <code>const struct nlmsghdr *nlhdr</code>
</li>
</ul>
</details>
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
