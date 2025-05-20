# Function: <code>devlink_nl_region_read_snapshot_fill</code>

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
In net/core/devlink.c (ffffffff8194c8fb)
Location: net/core/devlink.c:3730
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff819856fc)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff81a545f0)
Location: net/core/devlink.c:4222
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
**Symbols:**

```
ffffffff81a545f0-ffffffff81a54783: devlink_nl_region_read_snapshot_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5b540)
Location: net/core/devlink.c:4879
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
**Symbols:**

```
ffffffff81a5b540-ffffffff81a5b6d3: devlink_nl_region_read_snapshot_fill.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a47779)
Location: net/core/devlink.c:5082
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff81b00a99)
Location: net/core/devlink.c:5690
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff81c87926)
Location: net/core/devlink.c:6185
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/devlink.c (ffff800010c2dd30)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (c0d44ce8)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (c000000000d253b8)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffe0007a4da0)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff8192556c)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff818df31c)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff819766fc)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
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
In net/core/devlink.c (ffffffff81998bec)
Location: net/core/devlink.c:3778
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
</details>
</li>
</ul>

## Differences
