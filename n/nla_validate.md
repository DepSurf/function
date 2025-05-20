# Function: <code>nla_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415780)
Location: lib/nlattr.c:122
Inline: False
Direct callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81415780-ffffffff814157f0: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d4a0)
Location: lib/nlattr.c:122
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff8145d4a0-ffffffff8145d511: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147bf80)
Location: lib/nlattr.c:122
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff8147bf80-ffffffff8147bfee: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485280)
Location: lib/nlattr.c:123
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff81485280-ffffffff8148530d: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1390)
Location: lib/nlattr.c:175
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
**Symbols:**

```
ffffffff814c1390-ffffffff814c141d: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f26f0)
Location: lib/nlattr.c:175
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff814f26f0-ffffffff814f277a: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (ffffffff8150669a)
Location: lib/nlattr.c:332
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
**Symbols:**

```
ffffffff81506990-ffffffff81506a11: nla_validate.part.7 (STB_LOCAL)
ffffffff81506a20-ffffffff81506a2b: nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1ae78)
Location: include/net/netlink.h:836
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af901d)
Location: include/net/netlink.h:836
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1b098)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05c7d)
Location: include/net/netlink.h:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a02934)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af14ed)
Location: include/net/netlink.h:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab4f1e)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb19fd)
Location: include/net/netlink.h:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2f14f)
Location: include/net/netlink.h:849
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d450ad)
Location: include/net/netlink.h:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de1fef)
Location: include/net/netlink.h:866
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e54d)
Location: include/net/netlink.h:866
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e535ff)
Location: include/net/netlink.h:867
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e1fd)
Location: include/net/netlink.h:867
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f12d13)
Location: include/net/netlink.h:874
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034907)
Location: include/net/netlink.h:874
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
