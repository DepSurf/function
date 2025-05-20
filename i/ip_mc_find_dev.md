# Function: <code>ip_mc_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81795670)
Location: net/ipv4/igmp.c:1696
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_msfget
```
**Symbols:**

```
ffffffff81795670-ffffffff81795727: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81803060)
Location: net/ipv4/igmp.c:1709
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81803060-ffffffff81803117: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81834000)
Location: net/ipv4/igmp.c:1747
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81834000-ffffffff818340b7: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818555c0)
Location: net/ipv4/igmp.c:1756
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff818555c0-ffffffff81855691: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d5460)
Location: net/ipv4/igmp.c:1782
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff818d5460-ffffffff818d5531: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192bdc0)
Location: net/ipv4/igmp.c:1793
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff8192bdc0-ffffffff8192be99: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195b250)
Location: net/ipv4/igmp.c:1809
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff8195b250-ffffffff8195b329: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819bff40)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff819bff40-ffffffff819bfff6: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f6ae0)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff819f6ae0-ffffffff819f6b96: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae50c0)
Location: net/ipv4/igmp.c:1809
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81ae50c0-ffffffff81ae5176: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af1f90)
Location: net/ipv4/igmp.c:1809
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81af1f90-ffffffff81af2046: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81add780)
Location: net/ipv4/igmp.c:1817
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81add780-ffffffff81add836: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9cbf0)
Location: net/ipv4/igmp.c:1817
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81b9cbf0-ffffffff81b9cca6: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2ec80)
Location: net/ipv4/igmp.c:1824
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81d2ec80-ffffffff81d2ed64: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef6cd0)
Location: net/ipv4/igmp.c:1824
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81ef6cd0-ffffffff81ef6db4: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f56740)
Location: net/ipv4/igmp.c:1825
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81f56740-ffffffff81f56824: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201cbf0)
Location: net/ipv4/igmp.c:1827
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff8201cbf0-ffffffff8201ccd4: ip_mc_find_dev (STB_LOCAL)
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
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cad5f0)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffff800010cad5f0-ffff800010cad6c8: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dba4e0)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
c0dba4e0-c0dba5cc: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc3b90)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
c000000000dc3b90-c000000000dc3cc8: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe000807a60)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffe000807a60-ffffffe000807b14: ip_mc_find_dev (STB_LOCAL)
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
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81996880)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81996880-ffffffff81996936: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81950340)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81950340-ffffffff819503f6: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a01120)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81a01120-ffffffff81a011d6: ip_mc_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct in_device *ip_mc_find_dev(struct net *net, struct ip_mreqn *imr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0b610)
Location: net/ipv4/igmp.c:1811
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:__ip_mc_join_group
```
**Symbols:**

```
ffffffff81a0b610-ffffffff81a0b6c6: ip_mc_find_dev (STB_LOCAL)
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
