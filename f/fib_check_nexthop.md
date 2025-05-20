# Function: <code>fib_check_nexthop</code>

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
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d57b0)
Location: net/ipv4/nexthop.c:637
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff819d57b0-ffffffff819d57f6: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0c320)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff81a0c320-ffffffff81a0c366: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd160)
Location: net/ipv4/nexthop.c:710
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81afd160-ffffffff81afd20e: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0b140)
Location: net/ipv4/nexthop.c:838
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81b0b140-ffffffff81b0b1ee: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8cd0)
Location: net/ipv4/nexthop.c:1347
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81af8cd0-ffffffff81af8df2: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1347
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81d3e76b-ffffffff81d3e7c2: fib_check_nexthop.cold (STB_LOCAL)
ffffffff81bb96e0-ffffffff81bb9853: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1348
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff81f0b0ac-ffffffff81f0b103: fib_check_nexthop.cold (STB_LOCAL)
ffffffff81d4d6d0-ffffffff81d4d83e: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1348
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff820b2942-ffffffff820b2999: fib_check_nexthop.cold (STB_LOCAL)
ffffffff81f16fe0-ffffffff81f1714e: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1348
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff82133afa-ffffffff82133b51: fib_check_nexthop.cold (STB_LOCAL)
ffffffff81f76cc0-ffffffff81f76e2e: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1371
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
```
**Symbols:**

```
ffffffff82215506-ffffffff8221555d: fib_check_nexthop.cold (STB_LOCAL)
ffffffff8203d490-ffffffff8203d5fe: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc56f8)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffff800010cc56f8-ffff800010cc57ec: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd12d4)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
c0dd12d4-c0dd133c: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1ea0)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
c000000000de1ea0-c000000000de1f98: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe00081a366)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffe00081a366-ffffffe00081a430: fib_check_nexthop (STB_GLOBAL)
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
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ac0c0)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff819ac0c0-ffffffff819ac106: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965b80)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff81965b80-ffffffff81965bc6: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a16960)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff81a16960-ffffffff81a169a6: fib_check_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fib_check_nexthop(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a21390)
Location: net/ipv4/nexthop.c:639
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/nexthop.c:fib_check_nh_list
```
**Symbols:**

```
ffffffff81a21390-ffffffff81a213d6: fib_check_nexthop (STB_GLOBAL)
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
