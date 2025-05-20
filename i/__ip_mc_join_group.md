# Function: <code>__ip_mc_join_group</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192e750)
Location: net/ipv4/igmp.c:2144
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff8192e750-ffffffff8192e8a9: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195dc80)
Location: net/ipv4/igmp.c:2160
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff8195dc80-ffffffff8195ddd9: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c3020)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff819c3020-ffffffff819c3181: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f9bc0)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff819f9bc0-ffffffff819f9d21: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae7980)
Location: net/ipv4/igmp.c:2154
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81ae7980-ffffffff81ae7ae1: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af4860)
Location: net/ipv4/igmp.c:2154
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81af4860-ffffffff81af49c1: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81adfe90)
Location: net/ipv4/igmp.c:2162
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81adfe90-ffffffff81adffee: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:2162
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81b9f490-ffffffff81b9f5f8: __ip_mc_join_group (STB_LOCAL)
ffffffff81d3c560-ffffffff81d3c57b: __ip_mc_join_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:2169
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81d318c0-ffffffff81d31a49: __ip_mc_join_group (STB_LOCAL)
ffffffff81f08d92-ffffffff81f08dad: __ip_mc_join_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:2169
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81efa0d0-ffffffff81efa259: __ip_mc_join_group (STB_LOCAL)
ffffffff820b06e3-ffffffff820b06fe: __ip_mc_join_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:2170
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81f59b70-ffffffff81f59cf5: __ip_mc_join_group (STB_LOCAL)
ffffffff82131964-ffffffff8213197f: __ip_mc_join_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:2172
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff82020090-ffffffff82020215: __ip_mc_join_group (STB_LOCAL)
ffffffff82213322-ffffffff8221333d: __ip_mc_join_group.cold (STB_LOCAL)
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
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb0f98)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffff800010cb0f98-ffff800010cb1104: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbaf7c)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
c0dbaf7c-c0dbb0f0: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc74c0)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
c000000000dc74c0-c000000000dc76a4: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe0008085bc)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffe0008085bc-ffffffe00080873a: __ip_mc_join_group (STB_LOCAL)
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
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81999960)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81999960-ffffffff81999ac1: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81953420)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81953420-ffffffff81953581: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a04200)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81a04200-ffffffff81a04361: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ip_mc_join_group(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0e770)
Location: net/ipv4/igmp.c:2156
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group_ssm
  - net/ipv4/igmp.c:ip_mc_join_group
```
**Symbols:**

```
ffffffff81a0e770-ffffffff81a0e8d1: __ip_mc_join_group (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
