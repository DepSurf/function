# Function: <code>fib_gw_from_via</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c6370)
Location: net/ipv4/fib_frontend.c:682
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff819c6370-ffffffff819c6413: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fcf20)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff819fcf20-ffffffff819fcfc3: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeb940)
Location: net/ipv4/fib_frontend.c:675
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81aeb940-ffffffff81aeb9e3: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af8850)
Location: net/ipv4/fib_frontend.c:675
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81af8850-ffffffff81af88f3: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae3f70)
Location: net/ipv4/fib_frontend.c:677
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81ae3f70-ffffffff81ae4057: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba38c0)
Location: net/ipv4/fib_frontend.c:677
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81ba38c0-ffffffff81ba39a7: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d36140)
Location: net/ipv4/fib_frontend.c:680
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81d36140-ffffffff81d3621b: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efe760)
Location: net/ipv4/fib_frontend.c:680
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81efe760-ffffffff81efe83b: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5e1f0)
Location: net/ipv4/fib_frontend.c:683
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81f5e1f0-ffffffff81f5e2cb: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff820247b0)
Location: net/ipv4/fib_frontend.c:683
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff820247b0-ffffffff8202488f: fib_gw_from_via (STB_GLOBAL)
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
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb5030)
Location: net/ipv4/fib_frontend.c:683
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffff800010cb5030-ffff800010cb514c: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc09d0)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
**Symbols:**

```
c0dc09d0-c0dc0ad4: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc9d0)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
c000000000dcc9d0-c000000000dccad4: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080caee)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffe00080caee-ffffffe00080cbe4: fib_gw_from_via (STB_GLOBAL)
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
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199ccc0)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff8199ccc0-ffffffff8199cd63: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81956780)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81956780-ffffffff81956823: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a07560)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81a07560-ffffffff81a07603: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fib_gw_from_via(struct fib_config *cfg, struct nlattr *nla, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a11ca0)
Location: net/ipv4/fib_frontend.c:683
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
**Symbols:**

```
ffffffff81a11ca0-ffffffff81a11d43: fib_gw_from_via (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
