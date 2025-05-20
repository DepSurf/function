# Function: <code>devlink_nl_linecard_fill</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81c7ddb0)
Location: net/core/devlink.c:2061
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff81c7ddb0-ffffffff81c7dfd1: devlink_nl_linecard_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e36920)
Location: net/core/devlink.c:2360
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_doit
  - net/core/devlink.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff81e36920-ffffffff81e36bc7: devlink_nl_linecard_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff82040220)
Location: net/devlink/leftover.c:1732
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_get_doit
  - net/devlink/leftover.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff82040220-ffffffff820404c7: devlink_nl_linecard_fill.isra.0 (STB_LOCAL)
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
In net/devlink/linecard.c (ffffffff82119890)
Location: net/devlink/linecard.c:73
Inline: True
Direct callers:
  - net/devlink/linecard.c:devlink_nl_linecard_get_dump_one
  - net/devlink/linecard.c:devlink_nl_linecard_get_doit
  - net/devlink/linecard.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff82119890-ffffffff82119b24: devlink_nl_linecard_fill.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
