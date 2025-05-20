# Function: <code>nh_check_attr_group</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d4134)
Location: net/ipv4/nexthop.c:389
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0aca4)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nh_check_attr_group(struct net *net, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afb1f0)
Location: net/ipv4/nexthop.c:440
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81afb1f0-ffffffff81afb46f: nh_check_attr_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nh_check_attr_group(struct net *net, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b088b0)
Location: net/ipv4/nexthop.c:568
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81b088b0-ffffffff81b08b39: nh_check_attr_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4290)
Location: net/ipv4/nexthop.c:1042
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81af4290-ffffffff81af460f: nh_check_attr_group.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1042
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81bb4a00-ffffffff81bb4e17: nh_check_attr_group.constprop.0 (STB_LOCAL)
ffffffff81d3de12-ffffffff81d3dfa3: nh_check_attr_group.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1043
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81d484a0-ffffffff81d488b4: nh_check_attr_group.constprop.0 (STB_LOCAL)
ffffffff81f0a6e2-ffffffff81f0a87f: nh_check_attr_group.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1043
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81f11a40-ffffffff81f11e54: nh_check_attr_group.constprop.0 (STB_LOCAL)
ffffffff820b1f97-ffffffff820b2134: nh_check_attr_group.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1043
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff81f71730-ffffffff81f71b44: nh_check_attr_group.constprop.0 (STB_LOCAL)
ffffffff82133177-ffffffff82133314: nh_check_attr_group.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1043
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
**Symbols:**

```
ffffffff82037e90-ffffffff8203825f: nh_check_attr_group.constprop.0 (STB_LOCAL)
ffffffff82214b26-ffffffff82214d27: nh_check_attr_group.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4220)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcfc14)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de0178)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000819818)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aaa44)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81964504)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a152e4)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1fd24)
Location: net/ipv4/nexthop.c:391
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
