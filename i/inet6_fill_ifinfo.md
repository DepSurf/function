# Function: <code>inet6_fill_ifinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cb720)
Location: net/ipv6/addrconf.c:4948
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
```
**Symbols:**

```
ffffffff817cb720-ffffffff817cb98e: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81838750)
Location: net/ipv6/addrconf.c:5206
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81838750-ffffffff818389b8: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186a280)
Location: net/ipv6/addrconf.c:5258
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8186a280-ffffffff8186a4e8: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188e800)
Location: net/ipv6/addrconf.c:5362
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8188e800-ffffffff8188ea5f: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190fe50)
Location: net/ipv6/addrconf.c:5368
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8190fe50-ffffffff819100af: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81967260)
Location: net/ipv6/addrconf.c:5487
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81967260-ffffffff819674bf: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c870)
Location: net/ipv6/addrconf.c:5646
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8199c870-ffffffff8199cacc: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5740
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81a08a50-ffffffff81a08ca5: inet6_fill_ifinfo (STB_LOCAL)
ffffffff81a11249-ffffffff81a11264: inet6_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3f160)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81a3f160-ffffffff81a3f3b5: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34de0)
Location: net/ipv6/addrconf.c:5789
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81b34de0-ffffffff81b35035: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5820
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81b439f0-ffffffff81b43c5a: inet6_fill_ifinfo (STB_LOCAL)
ffffffff81c32b4d-ffffffff81c32b65: inet6_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5848
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81b31650-ffffffff81b318b9: inet6_fill_ifinfo (STB_LOCAL)
ffffffff81c24e5d-ffffffff81c24e75: inet6_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5895
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81bf76f0-ffffffff81bf7959: inet6_fill_ifinfo (STB_LOCAL)
ffffffff81d3f798-ffffffff81d3f7b0: inet6_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5914
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81d90b60-ffffffff81d90de4: inet6_fill_ifinfo (STB_LOCAL)
ffffffff81f0c13e-ffffffff81f0c156: inet6_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5f280)
Location: net/ipv6/addrconf.c:5927
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81f5f280-ffffffff81f5f51c: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbefb0)
Location: net/ipv6/addrconf.c:5933
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81fbefb0-ffffffff81fbf24a: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208c440)
Location: net/ipv6/addrconf.c:5990
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8208c440-ffffffff8208c6e5: inet6_fill_ifinfo (STB_LOCAL)
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
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d02620)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffff800010d02620-ffff800010d02878: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e08450)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
c0e08450-c0e086bc: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e29ec0)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
c000000000e29ec0-c000000000e2a1e4: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084aa8a)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffe00084aa8a-ffffffe00084ac5a: inet6_fill_ifinfo (STB_LOCAL)
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
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819de7f0)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff819de7f0-ffffffff819dea45: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199b5b0)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff8199b5b0-ffffffff8199b805: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a49270)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81a49270-ffffffff81a494c5: inet6_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_fill_ifinfo(struct sk_buff *skb, struct inet6_dev *idev, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a55190)
Location: net/ipv6/addrconf.c:5772
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
```
**Symbols:**

```
ffffffff81a55190-ffffffff81a553e5: inet6_fill_ifinfo (STB_LOCAL)
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
