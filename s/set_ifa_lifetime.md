# Function: <code>set_ifa_lifetime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817907d0)
Location: net/ipv4/devinet.c:718
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
**Symbols:**

```
ffffffff817907d0-ffffffff8179081a: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fdc60)
Location: net/ipv4/devinet.c:722
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff817fdc60-ffffffff817fdcaa: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ebc0)
Location: net/ipv4/devinet.c:722
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff8182ebc0-ffffffff8182ec0a: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818521c4)
Location: net/ipv4/devinet.c:743
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff8184ef20-ffffffff8184ef68: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d1fd0)
Location: net/ipv4/devinet.c:750
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff818cec90-ffffffff818cecd8: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81928524)
Location: net/ipv4/devinet.c:751
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819250e0-ffffffff81925128: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81957977)
Location: net/ipv4/devinet.c:761
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81953ef0-ffffffff81953f38: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819bc2eb)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819b8800-ffffffff819b8848: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f2fea)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819ef500-ffffffff819ef548: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ae19d7)
Location: net/ipv4/devinet.c:799
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81add450-ffffffff81add498: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aee877)
Location: net/ipv4/devinet.c:798
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81aea170-ffffffff81aea1b8: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad9f6f)
Location: net/ipv4/devinet.c:798
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81ad58d0-ffffffff81ad5918: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b990af)
Location: net/ipv4/devinet.c:798
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81b94790-ffffffff81b947d8: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d2afc9)
Location: net/ipv4/devinet.c:799
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81d260b0-ffffffff81d26106: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef2be4)
Location: net/ipv4/devinet.c:800
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81eed8f0-ffffffff81eed946: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f52792)
Location: net/ipv4/devinet.c:800
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81f4d2b0-ffffffff81f4d306: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82018a74)
Location: net/ipv4/devinet.c:803
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff820133c0-ffffffff82013416: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca9388)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffff800010ca5330-ffff800010ca53c0: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db5990)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
c0db1b94-c0db1c28: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbe508)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
c000000000db90d0-c000000000db914c: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000803e5c)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffe000800bb4-ffffffe000800c20: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81992d8a)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff8198f2a0-ffffffff8198f2e8: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194c84a)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81948d60-ffffffff81948da8: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fd62a)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819f9b40-ffffffff819f9b88: set_ifa_lifetime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_ifa_lifetime(struct in_ifaddr *ifa, __u32 valid_lft, __u32 prefered_lft);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a079ba)
Location: net/ipv4/devinet.c:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81a03e30-ffffffff81a03e78: set_ifa_lifetime (STB_LOCAL)
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
