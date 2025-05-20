# Function: <code>lwtunnel_valid_encap_type_attr</code>

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
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817d9670)
Location: net/core/lwtunnel.c:160
Inline: False
Direct callers:
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff817d9670-ffffffff817d9720: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff817f8b00)
Location: net/core/lwtunnel.c:180
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff817f8b00-ffffffff817f8bb3: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818763e0)
Location: net/core/lwtunnel.c:182
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818763e0-ffffffff81876493: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818c7b20)
Location: net/core/lwtunnel.c:182
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818c7b20-ffffffff818c7bac: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818f0c80)
Location: net/core/lwtunnel.c:182
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818f0c80-ffffffff818f0d0c: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81942390)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81942390-ffffffff81942412: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819772c0)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff819772c0-ffffffff81977342: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a4c0b0)
Location: net/core/lwtunnel.c:179
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a4c0b0-ffffffff81a4c132: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a51ce0)
Location: net/core/lwtunnel.c:179
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a51ce0-ffffffff81a51d62: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81a375e0)
Location: net/core/lwtunnel.c:179
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81a375e0-ffffffff81a37662: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81aed2d0)
Location: net/core/lwtunnel.c:184
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81aed2d0-ffffffff81aed38a: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81c6ff40)
Location: net/core/lwtunnel.c:184
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81c6ff40-ffffffff81c70007: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e27e90)
Location: net/core/lwtunnel.c:187
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81e27e90-ffffffff81e27f57: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81e9d4a0)
Location: net/core/lwtunnel.c:187
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81e9d4a0-ffffffff81e9d567: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81f5fc20)
Location: net/core/lwtunnel.c:187
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81f5fc20-ffffffff81f5fcef: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
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
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffff800010c1dc18)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffff800010c1dc18-ffff800010c1dcc4: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c0d358b0)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
c0d358b0-c0d3594c: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (c000000000d0f190)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
c000000000d0f190-c000000000d0f298: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffe0007977ae)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffe0007977ae-ffffffe00079783a: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
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
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff81917130)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff81917130-ffffffff819171b2: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff818d0ee0)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff818d0ee0-ffffffff818d0f62: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff819682c0)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff819682c0-ffffffff81968342: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type_attr(struct nlattr *attr, int remaining, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwtunnel.c (ffffffff8198a580)
Location: net/core/lwtunnel.c:177
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv6/route.c:rtm_to_fib6_config
```
**Symbols:**

```
ffffffff8198a580-ffffffff8198a602: lwtunnel_valid_encap_type_attr (STB_GLOBAL)
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
