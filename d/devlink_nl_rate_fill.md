# Function: <code>devlink_nl_rate_fill</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81afd320)
Location: net/core/devlink.c:850
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff81afd320-ffffffff81afd50a: devlink_nl_rate_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c835a0)
Location: net/core/devlink.c:1068
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff81c835a0-ffffffff81c837a0: devlink_nl_rate_fill.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e3b9d0)
Location: net/core/devlink.c:1244
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_get_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff81e3b9d0-ffffffff81e3bc1c: devlink_nl_rate_fill.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff8203e050)
Location: net/devlink/leftover.c:719
Inline: True
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_get_dump_one
  - net/devlink/leftover.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff8203e050-ffffffff8203e2f4: devlink_nl_rate_fill.isra.0 (STB_LOCAL)
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
In net/devlink/rate.c (ffffffff821187c0)
Location: net/devlink/rate.c:83
Inline: True
Direct callers:
  - net/devlink/rate.c:devlink_nl_rate_get_doit
  - net/devlink/rate.c:devlink_nl_rate_get_dump_one
  - net/devlink/rate.c:devlink_rate_notify
```
**Symbols:**

```
ffffffff821187c0-ffffffff82118a64: devlink_nl_rate_fill.isra.0 (STB_LOCAL)
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
