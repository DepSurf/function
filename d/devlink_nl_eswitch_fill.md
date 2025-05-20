# Function: <code>devlink_nl_eswitch_fill</code>

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
In net/core/devlink.c (ffffffff8194932e)
Location: net/core/devlink.c:1564
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffff8197ea9e)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a56510)
Location: net/core/devlink.c:1598
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81a56510-ffffffff81a566b7: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d950)
Location: net/core/devlink.c:1930
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81a5d950-ffffffff81a5dafa: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a3fba0)
Location: net/core/devlink.c:2133
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81a3fba0-ffffffff81a3fd49: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81af6a20)
Location: net/core/devlink.c:2675
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81af6a20-ffffffff81af6bc9: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c7a4b0)
Location: net/core/devlink.c:3194
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81c7a4b0-ffffffff81c7a680: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e32e10)
Location: net/core/devlink.c:3458
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff81e32e10-ffffffff81e32fe0: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/dev.c (ffffffff82043a60)
Location: net/devlink/dev.c:529
Inline: True
Direct callers:
  - net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit
```
**Symbols:**

```
ffffffff82043a60-ffffffff82043ca7: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/dev.c (ffffffff82102c40)
Location: net/devlink/dev.c:630
Inline: True
Direct callers:
  - net/devlink/dev.c:devlink_nl_eswitch_get_doit
```
**Symbols:**

```
ffffffff82102c40-ffffffff82102e87: devlink_nl_eswitch_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c26974)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (c0d3d938)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (c000000000d1ae94)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffe00079f790)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffff8191e90e)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffff818d86be)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffff8196fa9e)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
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
In net/core/devlink.c (ffffffff81991f8e)
Location: net/core/devlink.c:1566
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
</details>
</li>
</ul>

## Differences
