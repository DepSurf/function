# Function: <code>fib_get_nhs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179ccb7)
Location: net/ipv4/fib_semantics.c:470
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180a8f5)
Location: net/ipv4/fib_semantics.c:470
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183ba03)
Location: net/ipv4/fib_semantics.c:471
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185d39c)
Location: net/ipv4/fib_semantics.c:483
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dd3d5)
Location: net/ipv4/fib_semantics.c:484
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81933e38)
Location: net/ipv4/fib_semantics.c:484
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81963324)
Location: net/ipv4/fib_semantics.c:482
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819c82c0-ffffffff819c873d: fib_get_nhs (STB_LOCAL)
ffffffff819cb072-ffffffff819cb093: fib_get_nhs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fee70)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819fee70-ffffffff819ff2f4: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aee400)
Location: net/ipv4/fib_semantics.c:667
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81aee400-ffffffff81aee87f: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afb360)
Location: net/ipv4/fib_semantics.c:667
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81afb360-ffffffff81afb7df: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae6a50)
Location: net/ipv4/fib_semantics.c:668
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ae6a50-ffffffff81ae6f1c: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:686
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ba66a0-ffffffff81ba6c15: fib_get_nhs (STB_LOCAL)
ffffffff81d3cc4a-ffffffff81d3cce4: fib_get_nhs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:688
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81d390a0-ffffffff81d395ab: fib_get_nhs (STB_LOCAL)
ffffffff81f094ac-ffffffff81f0952e: fib_get_nhs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:690
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f01970-ffffffff81f01e7b: fib_get_nhs (STB_LOCAL)
ffffffff820b0d88-ffffffff820b0e0a: fib_get_nhs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:690
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f613d0-ffffffff81f618db: fib_get_nhs (STB_LOCAL)
ffffffff82132012-ffffffff82132094: fib_get_nhs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:691
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff820279a0-ffffffff82027ead: fib_get_nhs (STB_LOCAL)
ffffffff822139d0-ffffffff82213a52: fib_get_nhs.cold (STB_LOCAL)
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
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb7450)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffff800010cb7450-ffff800010cb77fc: fib_get_nhs (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (c0dc39e8)
Location: net/ipv4/fib_semantics.c:658
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcf990)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c000000000dcf990-c000000000dcfe34: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080e7bc)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffe00080e7bc-ffffffe00080ea68: fib_get_nhs (STB_LOCAL)
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
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199ec10)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8199ec10-ffffffff8199f094: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819586d0)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819586d0-ffffffff81958b54: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a094b0)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a094b0-ffffffff81a09934: fib_get_nhs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_get_nhs(struct fib_info *fi, struct rtnexthop *rtnh, int remaining, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a13c60)
Location: net/ipv4/fib_semantics.c:658
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a13c60-ffffffff81a140e4: fib_get_nhs (STB_LOCAL)
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
