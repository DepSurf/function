# Function: <code>fib_check_nh_v4_gw</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c79f0)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819c79f0-ffffffff819c7cdf: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fe5a0)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff819fe5a0-ffffffff819fe88f: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aece70)
Location: net/ipv4/fib_semantics.c:1063
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81aece70-ffffffff81aed166: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9ac0)
Location: net/ipv4/fib_semantics.c:1063
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81af9ac0-ffffffff81af9deb: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae51b0)
Location: net/ipv4/fib_semantics.c:1064
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81ae51b0-ffffffff81ae552d: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1106
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81ba4e80-ffffffff81ba5210: fib_check_nh_v4_gw (STB_LOCAL)
ffffffff81d3c88e-ffffffff81d3c8a3: fib_check_nh_v4_gw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1113
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81d37820-ffffffff81d37be2: fib_check_nh_v4_gw (STB_LOCAL)
ffffffff81f090ed-ffffffff81f09109: fib_check_nh_v4_gw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1119
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81f00380-ffffffff81f00742: fib_check_nh_v4_gw (STB_LOCAL)
ffffffff820b0a55-ffffffff820b0a71: fib_check_nh_v4_gw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1119
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81f5fe00-ffffffff81f601c2: fib_check_nh_v4_gw (STB_LOCAL)
ffffffff82131cdc-ffffffff82131cf8: fib_check_nh_v4_gw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff820263d0-ffffffff82026798: fib_check_nh_v4_gw (STB_LOCAL)
ffffffff8221369a-ffffffff822136b6: fib_check_nh_v4_gw.cold (STB_LOCAL)
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
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6c28)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffff800010cb6c28-ffff800010cb6f5c: fib_check_nh_v4_gw (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (c0dc2f38)
Location: net/ipv4/fib_semantics.c:1054
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dceee0)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
c000000000dceee0-c000000000dcf348: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080de86)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffe00080de86-ffffffe00080e12e: fib_check_nh_v4_gw (STB_LOCAL)
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
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199e340)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff8199e340-ffffffff8199e62f: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81957e00)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81957e00-ffffffff819580ef: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08be0)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81a08be0-ffffffff81a08ecf: fib_check_nh_v4_gw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_check_nh_v4_gw(struct net *net, struct fib_nh *nh, u32 table, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a13340)
Location: net/ipv4/fib_semantics.c:1054
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
```
**Symbols:**

```
ffffffff81a13340-ffffffff81a13678: fib_check_nh_v4_gw (STB_LOCAL)
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
