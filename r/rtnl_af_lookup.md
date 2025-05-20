# Function: <code>rtnl_af_lookup</code>

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
In net/core/rtnetlink.c (ffffffff81729b98)
Location: net/core/rtnetlink.c:450
Inline: True
Inline callers:
  - net/core/rtnetlink.c:validate_linkmsg
  - net/core/rtnetlink.c:do_setlink
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
In net/core/rtnetlink.c (ffffffff81795ca4)
Location: net/core/rtnetlink.c:472
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff817c31f6)
Location: net/core/rtnetlink.c:473
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff817e1eb3)
Location: net/core/rtnetlink.c:475
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff8185caf6)
Location: net/core/rtnetlink.c:452
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff818a8746)
Location: net/core/rtnetlink.c:535
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff818cc8cb)
Location: net/core/rtnetlink.c:545
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff8191972a)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff8194bd4a)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff81a1c93e)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff81a1cce7)
Location: net/core/rtnetlink.c:542
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ffcf0)
Location: net/core/rtnetlink.c:542
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff819ffcf0-ffffffff819ffd67: rtnl_af_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:542
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff81ab27c0-ffffffff81ab2846: rtnl_af_lookup (STB_LOCAL)
ffffffff81d36daf-ffffffff81d36dc4: rtnl_af_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:579
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff81c2b950-ffffffff81c2b9ea: rtnl_af_lookup (STB_LOCAL)
ffffffff81f036c3-ffffffff81f036d8: rtnl_af_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:580
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff81dde5f0-ffffffff81dde68a: rtnl_af_lookup (STB_LOCAL)
ffffffff820abe58-ffffffff820abe6d: rtnl_af_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:583
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff81e4f490-ffffffff81e4f52a: rtnl_af_lookup (STB_LOCAL)
ffffffff8212d59a-ffffffff8212d5af: rtnl_af_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct rtnl_af_ops *rtnl_af_lookup(const int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:578
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
**Symbols:**

```
ffffffff81f0e4d0-ffffffff81f0e56a: rtnl_af_lookup (STB_LOCAL)
ffffffff8220f2e7-ffffffff8220f2fc: rtnl_af_lookup.cold (STB_LOCAL)
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
In net/core/rtnetlink.c (ffff800010bed200)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (c0d05794)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (c000000000cd13e0)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffe00076f770)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff818ebd1a)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff818a5b5a)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff8193cd4a)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
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
In net/core/rtnetlink.c (ffffffff8195e5c3)
Location: net/core/rtnetlink.c:540
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:validate_linkmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
