# Function: <code>fib_check_nh_list</code>

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
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d5800)
Location: net/ipv4/nexthop.c:661
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819d5800-ffffffff819d585e: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0c370)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a0c370-ffffffff81a0c3ce: fib_check_nh_list (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81afd215)
Location: net/ipv4/nexthop.c:749
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81b0b20c)
Location: net/ipv4/nexthop.c:877
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81af8e18)
Location: net/ipv4/nexthop.c:1386
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81bb9878)
Location: net/ipv4/nexthop.c:1386
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81d4d858)
Location: net/ipv4/nexthop.c:1387
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81f17178)
Location: net/ipv4/nexthop.c:1387
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff81f76e58)
Location: net/ipv4/nexthop.c:1387
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
In net/ipv4/nexthop.c (ffffffff8203d628)
Location: net/ipv4/nexthop.c:1410
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:replace_nexthop
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
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc57f0)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffff800010cc57f0-ffff800010cc5870: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd133c)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c0dd133c-c0dd139c: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1fa0)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
c000000000de1fa0-c000000000de2064: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe00081a430)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffe00081a430-ffffffe00081a49e: fib_check_nh_list (STB_LOCAL)
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
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ac110)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff819ac110-ffffffff819ac16e: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965bd0)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81965bd0-ffffffff81965c2e: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a169b0)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a169b0-ffffffff81a16a0e: fib_check_nh_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_check_nh_list(struct nexthop *old, struct nexthop *new, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a213e0)
Location: net/ipv4/nexthop.c:663
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81a213e0-ffffffff81a2143e: fib_check_nh_list (STB_LOCAL)
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
