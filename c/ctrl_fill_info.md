# Function: <code>ctrl_fill_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ctrl_fill_info(struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8174fba0)
Location: net/netlink/genetlink.c:690
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8174fba0-ffffffff8174ffeb: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ctrl_fill_info(struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bbb80)
Location: net/netlink/genetlink.c:685
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff817bbb80-ffffffff817bbfb2: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817eb4c0)
Location: net/netlink/genetlink.c:641
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff817eb4c0-ffffffff817eb8f2: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180b480)
Location: net/netlink/genetlink.c:644
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8180b480-ffffffff8180b87c: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8188a410)
Location: net/netlink/genetlink.c:645
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8188a410-ffffffff8188a80c: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818dda30)
Location: net/netlink/genetlink.c:647
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff818dda30-ffffffff818dde31: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8190a3f0)
Location: net/netlink/genetlink.c:648
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8190a3f0-ffffffff8190a7f1: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8196b810-ffffffff8196bc02: ctrl_fill_info (STB_LOCAL)
ffffffff8196ceab-ffffffff8196cece: ctrl_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a21c0)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff819a21c0-ffffffff819a25b9: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7c820)
Location: net/netlink/genetlink.c:752
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81a7c820-ffffffff81a7cc2c: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:821
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81a85b90-ffffffff81a85fa4: ctrl_fill_info (STB_LOCAL)
ffffffff81c322f7-ffffffff81c3230f: ctrl_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:821
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81a6e880-ffffffff81a6ecb1: ctrl_fill_info (STB_LOCAL)
ffffffff81c245e0-ffffffff81c245f8: ctrl_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:813
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81b282c0-ffffffff81b286f1: ctrl_fill_info (STB_LOCAL)
ffffffff81d3957a-ffffffff81d39592: ctrl_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (0)
Location: net/netlink/genetlink.c:813
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81cb14c0-ffffffff81cb1928: ctrl_fill_info (STB_LOCAL)
ffffffff81f05cd1-ffffffff81f05ce9: ctrl_fill_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6f290)
Location: net/netlink/genetlink.c:1086
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81e6f290-ffffffff81e6f747: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ecb710)
Location: net/netlink/genetlink.c:1088
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81ecb710-ffffffff81ecbbc7: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8ec30)
Location: net/netlink/genetlink.c:1227
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81f8ec30-ffffffff81f8f0ed: ctrl_fill_info (STB_LOCAL)
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
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c513e8)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffff800010c513e8-ffff800010c517f8: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d60b58)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
c0d60b58-c0d60f30: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d4fc40)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
c000000000d4fc40-c000000000d50178: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bc6de)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffe0007bc6de-ffffffe0007bc9d8: ctrl_fill_info (STB_LOCAL)
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
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81942030)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81942030-ffffffff81942429: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fbb20)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff818fbb20-ffffffff818fbf19: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819931c0)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff819931c0-ffffffff819935b9: ctrl_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ctrl_fill_info(const struct genl_family *family, u32 portid, u32 seq, u32 flags, struct sk_buff *skb, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b5cb0)
Location: net/netlink/genetlink.c:675
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_build_family_msg
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff819b5cb0-ffffffff819b60a9: ctrl_fill_info (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct genl_family *family</code> ➡️ <code>const struct genl_family *family</code>
</li>
</ul>
</details>
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
