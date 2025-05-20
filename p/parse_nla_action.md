# Function: <code>parse_nla_action</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8194f0e2)
Location: net/ipv6/seg6_local.c:750
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819a83c4)
Location: net/ipv6/seg6_local.c:906
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819def14)
Location: net/ipv6/seg6_local.c:918
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a4da7d)
Location: net/ipv6/seg6_local.c:914
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffff81a8464d)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7edb0)
Location: net/ipv6/seg6_local.c:941
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81b7edb0-ffffffff81b7ee69: parse_nla_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8f620)
Location: net/ipv6/seg6_local.c:1459
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81b8f620-ffffffff81b8f87c: parse_nla_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7e220)
Location: net/ipv6/seg6_local.c:1643
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81b7e220-ffffffff81b7e44d: parse_nla_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1708
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81c48a30-ffffffff81c48ca3: parse_nla_action (STB_LOCAL)
ffffffff81d41624-ffffffff81d41638: parse_nla_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1708
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81de8130-ffffffff81de836a: parse_nla_action (STB_LOCAL)
ffffffff81f0df98-ffffffff81f0dfac: parse_nla_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:2036
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff81fbaee0-ffffffff81fbb12f: parse_nla_action (STB_LOCAL)
ffffffff820b5340-ffffffff820b5354: parse_nla_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:2363
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff8201b5a0-ffffffff8201b7ef: parse_nla_action (STB_LOCAL)
ffffffff821361d1-ffffffff821361e5: parse_nla_action.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_nla_action(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:2426
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
**Symbols:**

```
ffffffff820ea560-ffffffff820ea7af: parse_nla_action (STB_LOCAL)
ffffffff82217da1-ffffffff82217db5: parse_nla_action.cold (STB_LOCAL)
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
In net/ipv6/seg6_local.c (ffff800010d50640)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (c0e511c0)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (c000000000e881e8)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffe000888bee)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffff81a23cdd)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffff819e0a9d)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffff81a8e75d)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
In net/ipv6/seg6_local.c (ffffffff81a9b4cd)
Location: net/ipv6/seg6_local.c:927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
