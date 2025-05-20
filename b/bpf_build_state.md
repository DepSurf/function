# Function: <code>bpf_build_state</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_build_state(struct net_device *dev, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817d9c30)
Location: net/core/lwt_bpf.c:240
Inline: False
```
**Symbols:**

```
ffffffff817d9c30-ffffffff817d9d9f: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f9270)
Location: net/core/lwt_bpf.c:241
Inline: False
```
**Symbols:**

```
ffffffff817f9270-ffffffff817f93e6: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876b80)
Location: net/core/lwt_bpf.c:241
Inline: False
```
**Symbols:**

```
ffffffff81876b80-ffffffff81876cf6: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818c8340)
Location: net/core/lwt_bpf.c:241
Inline: False
```
**Symbols:**

```
ffffffff818c8340-ffffffff818c84ca: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818f14b0)
Location: net/core/lwt_bpf.c:240
Inline: False
```
**Symbols:**

```
ffffffff818f14b0-ffffffff818f163a: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81942dd0)
Location: net/core/lwt_bpf.c:367
Inline: False
```
**Symbols:**

```
ffffffff81942dd0-ffffffff81942f61: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81977d80)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81977d80-ffffffff81977f11: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4d0c0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81a4d0c0-ffffffff81a4d243: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a52d80)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81a52d80-ffffffff81a52f03: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a38580)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81a38580-ffffffff81a38715: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee3f0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81aee3f0-ffffffff81aee585: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c712b0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81c712b0-ffffffff81c71478: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e29360)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81e29360-ffffffff81e29528: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9e990)
Location: net/core/lwt_bpf.c:369
Inline: False
```
**Symbols:**

```
ffffffff81e9e990-ffffffff81e9eb58: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f61100)
Location: net/core/lwt_bpf.c:369
Inline: False
```
**Symbols:**

```
ffffffff81f61100-ffffffff81f612cb: bpf_build_state (STB_LOCAL)
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
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1e5d0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffff800010c1e5d0-ffff800010c1e790: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d36620)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
c0d36620-c0d367e8: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d105b0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
c000000000d105b0-c000000000d10808: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe0007982c6)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffe0007982c6-ffffffe000798426: bpf_build_state (STB_LOCAL)
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
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81917bf0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81917bf0-ffffffff81917d81: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818d19a0)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff818d19a0-ffffffff818d1b31: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81968d80)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff81968d80-ffffffff81968f11: bpf_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_build_state(struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff8198b160)
Location: net/core/lwt_bpf.c:370
Inline: False
```
**Symbols:**

```
ffffffff8198b160-ffffffff8198b2f1: bpf_build_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, nla, family, cfg, ts</code> ➡️ <code>nla, family, cfg, ts, extack</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>nla, family, cfg, ts, extack</code> ➡️ <code>net, nla, family, cfg, ts, extack</code>
</li>
</ul>
</details>
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
