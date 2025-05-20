# Function: <code>remove_nh_grp_entry</code>

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
In net/ipv4/nexthop.c (ffffffff819d52f5)
Location: net/ipv4/nexthop.c:695
Inline: True
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
In net/ipv4/nexthop.c (ffffffff81a0be55)
Location: net/ipv4/nexthop.c:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc830)
Location: net/ipv4/nexthop.c:783
Inline: False
```
**Symbols:**

```
ffffffff81afc830-ffffffff81afca16: remove_nh_grp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:911
Inline: False
```
**Symbols:**

```
ffffffff81b0a660-ffffffff81b0a893: remove_nh_grp_entry (STB_LOCAL)
ffffffff81c32a03-ffffffff81c32a18: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1732
Inline: False
```
**Symbols:**

```
ffffffff81af7c90-ffffffff81af7f0e: remove_nh_grp_entry (STB_LOCAL)
ffffffff81c24cfc-ffffffff81c24d11: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1732
Inline: False
```
**Symbols:**

```
ffffffff81bb8980-ffffffff81bb8c65: remove_nh_grp_entry (STB_LOCAL)
ffffffff81d3e4da-ffffffff81d3e581: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1733
Inline: False
```
**Symbols:**

```
ffffffff81d4c850-ffffffff81d4cb8e: remove_nh_grp_entry (STB_LOCAL)
ffffffff81f0add1-ffffffff81f0aeb8: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1733
Inline: False
```
**Symbols:**

```
ffffffff81f16080-ffffffff81f1641e: remove_nh_grp_entry (STB_LOCAL)
ffffffff820b265a-ffffffff820b274e: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1733
Inline: False
```
**Symbols:**

```
ffffffff81f75d30-ffffffff81f760ce: remove_nh_grp_entry (STB_LOCAL)
ffffffff82133812-ffffffff82133906: remove_nh_grp_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void remove_nh_grp_entry(struct net *net, struct nh_grp_entry *nhge, struct nl_info *nlinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1756
Inline: False
```
**Symbols:**

```
ffffffff8203c500-ffffffff8203c89e: remove_nh_grp_entry (STB_LOCAL)
ffffffff8221521e-ffffffff82215312: remove_nh_grp_entry.cold (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc51cc)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (c0dd0c48)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (c000000000de1644)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (ffffffe00081908a)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (ffffffff819abbf5)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (ffffffff819656b5)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (ffffffff81a16495)
Location: net/ipv4/nexthop.c:697
Inline: True
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
In net/ipv4/nexthop.c (ffffffff81a20ed5)
Location: net/ipv4/nexthop.c:697
Inline: True
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
