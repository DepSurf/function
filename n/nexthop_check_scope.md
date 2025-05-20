# Function: <code>nexthop_check_scope</code>

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
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d3b30)
Location: net/ipv4/nexthop.c:613
Inline: True
```
**Symbols:**

```
ffffffff819d3b30-ffffffff819d3b7f: nexthop_check_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a6a0)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
ffffffff81a0a6a0-ffffffff81a0a6ef: nexthop_check_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd182)
Location: net/ipv4/nexthop.c:689
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0b162)
Location: net/ipv4/nexthop.c:817
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8cfe)
Location: net/ipv4/nexthop.c:1326
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb9737)
Location: net/ipv4/nexthop.c:1326
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4d727)
Location: net/ipv4/nexthop.c:1327
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f17037)
Location: net/ipv4/nexthop.c:1327
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f76d17)
Location: net/ipv4/nexthop.c:1327
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203d4e7)
Location: net/ipv4/nexthop.c:1350
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:fib_check_nexthop
  - net/ipv4/nexthop.c:fib_check_nexthop
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
In net/ipv4/nexthop.c (ffff800010cc572c)
Location: net/ipv4/nexthop.c:615
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dcf9fc)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
c0dcf9fc-c0dcfa80: nexthop_check_scope (STB_LOCAL)
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
In net/ipv4/nexthop.c (c000000000de1ec4)
Location: net/ipv4/nexthop.c:615
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
In net/ipv4/nexthop.c (ffffffe00081a392)
Location: net/ipv4/nexthop.c:615
Inline: True
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
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819aa440)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
ffffffff819aa440-ffffffff819aa48f: nexthop_check_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81963f00)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
ffffffff81963f00-ffffffff81963f4f: nexthop_check_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a14ce0)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
ffffffff81a14ce0-ffffffff81a14d2f: nexthop_check_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nexthop_check_scope(struct nexthop *nh, u8 scope, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f6f0)
Location: net/ipv4/nexthop.c:615
Inline: True
```
**Symbols:**

```
ffffffff81a1f6f0-ffffffff81a1f73f: nexthop_check_scope (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
