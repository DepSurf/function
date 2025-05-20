# Function: <code>devlink_dpipe_tables_fill</code>

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
In net/core/devlink.c (ffffffff81951626)
Location: net/core/devlink.c:1836
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff81988066)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff81a600e0)
Location: net/core/devlink.c:1870
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81a600e0-ffffffff81a6033e: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a688d0)
Location: net/core/devlink.c:2202
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81a688d0-ffffffff81a68b24: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a4bb70)
Location: net/core/devlink.c:2405
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81a4bb70-ffffffff81a4bdb5: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81b03180)
Location: net/core/devlink.c:2967
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81b03180-ffffffff81b033c5: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c847d0)
Location: net/core/devlink.c:3482
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81c847d0-ffffffff81c84a3c: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e3e910)
Location: net/core/devlink.c:3746
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81e3e910-ffffffff81e3eb7c: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff8203ef90)
Location: net/devlink/leftover.c:2964
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8203ef90-ffffffff8203f251: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/dpipe.c (ffffffff8210bbb0)
Location: net/devlink/dpipe.c:212
Inline: True
Direct callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_table_get_doit
```
**Symbols:**

```
ffffffff8210bbb0-ffffffff8210be71: devlink_dpipe_tables_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c30258)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (c0d47204)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (c000000000d28a08)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffe0007a6492)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff81927ed6)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff818e1c86)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff81979066)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
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
In net/core/devlink.c (ffffffff8199b556)
Location: net/core/devlink.c:1838
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
</details>
</li>
</ul>

## Differences
