# Function: <code>ip_mc_join_group_ssm</code>

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
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192f750)
Location: net/ipv4/igmp.c:2204
Inline: False
```
**Symbols:**

```
ffffffff8192f750-ffffffff8192f760: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195ec30)
Location: net/ipv4/igmp.c:2220
Inline: False
```
**Symbols:**

```
ffffffff8195ec30-ffffffff8195ec40: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c3ab0)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff819c3ab0-ffffffff819c3ac0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819fa650)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff819fa650-ffffffff819fa660: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae8fe0)
Location: net/ipv4/igmp.c:2214
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81ae8fe0-ffffffff81ae8ff0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af5e70)
Location: net/ipv4/igmp.c:2214
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81af5e70-ffffffff81af5e80: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae15d0)
Location: net/ipv4/igmp.c:2222
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81ae15d0-ffffffff81ae15e0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ba0cd0)
Location: net/ipv4/igmp.c:2222
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81ba0cd0-ffffffff81ba0ce0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d331e0)
Location: net/ipv4/igmp.c:2229
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81d331e0-ffffffff81d331fa: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81efb4e0)
Location: net/ipv4/igmp.c:2229
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81efb4e0-ffffffff81efb4fa: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f5af70)
Location: net/ipv4/igmp.c:2230
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff81f5af70-ffffffff81f5af8a: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff820214b0)
Location: net/ipv4/igmp.c:2232
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_mcast_group_source
```
**Symbols:**

```
ffffffff820214b0-ffffffff820214ca: ip_mc_join_group_ssm (STB_GLOBAL)
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
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb1d90)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffff800010cb1d90-ffff800010cb1dd4: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbd9d4)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
c0dbd9d4-c0dbd9f0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc8de0)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
c000000000dc8de0-c000000000dc8df4: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080a73a)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffe00080a73a-ffffffe00080a774: ip_mc_join_group_ssm (STB_GLOBAL)
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
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8199a3f0)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff8199a3f0-ffffffff8199a400: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81953eb0)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff81953eb0-ffffffff81953ec0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a04c90)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff81a04c90-ffffffff81a04ca0: ip_mc_join_group_ssm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_mc_join_group_ssm(struct sock *sk, struct ip_mreqn *imr, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0f220)
Location: net/ipv4/igmp.c:2216
Inline: False
```
**Symbols:**

```
ffffffff81a0f220-ffffffff81a0f230: ip_mc_join_group_ssm (STB_GLOBAL)
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
