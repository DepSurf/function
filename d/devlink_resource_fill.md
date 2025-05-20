# Function: <code>devlink_resource_fill</code>

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
In net/core/devlink.c (ffffffff8194ace0)
Location: net/core/devlink.c:2572
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff8197f700)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff81a57a40)
Location: net/core/devlink.c:2606
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81a57a40-ffffffff81a57c4a: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5f790)
Location: net/core/devlink.c:2938
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81a5f790-ffffffff81a5f99a: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a41270)
Location: net/core/devlink.c:3141
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81a41270-ffffffff81a414a7: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81af8b50)
Location: net/core/devlink.c:3703
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81af8b50-ffffffff81af8d87: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c7cd30)
Location: net/core/devlink.c:4218
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81c7cd30-ffffffff81c7cf7e: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e353c0)
Location: net/core/devlink.c:4484
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff81e353c0-ffffffff81e3560e: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff820382d0)
Location: net/devlink/leftover.c:3702
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_resource_dump
```
**Symbols:**

```
ffffffff820382d0-ffffffff82038579: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/resource.c (ffffffff8210c730)
Location: net/devlink/resource.c:219
Inline: True
Direct callers:
  - net/devlink/resource.c:devlink_nl_resource_dump_doit
```
**Symbols:**

```
ffffffff8210c730-ffffffff8210c9c5: devlink_resource_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c280cc)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (c0d3e278)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (c000000000d1d5c0)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffe0007a084c)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff8191f570)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff818d9320)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff81970700)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
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
In net/core/devlink.c (ffffffff81992bf0)
Location: net/core/devlink.c:2574
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
```
</details>
</li>
</ul>

## Differences
