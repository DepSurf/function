# Function: <code>devlink_port_get_from_info</code>

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
In net/core/devlink.c (ffffffff81946b48)
Location: net/core/devlink.c:167
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff8197bb98)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81a51050)
Location: net/core/devlink.c:180
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81a59c47)
Location: net/core/devlink.c:184
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81a3ce1e)
Location: net/core/devlink.c:187
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81af3d1e)
Location: net/core/devlink.c:188
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81c87bc0)
Location: net/core/devlink.c:339
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81e43c86)
Location: net/core/devlink.c:408
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_port *devlink_port_get_from_info(struct devlink *devlink, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820410b0)
Location: net/devlink/leftover.c:174
Inline: False
Direct callers:
  - net/devlink/netlink.c:devlink_nl_pre_doit
  - net/devlink/netlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff820410b0-ffffffff820410fe: devlink_port_get_from_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_port *devlink_port_get_from_info(struct devlink *devlink, struct genl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff821079c0)
Location: net/devlink/port.c:47
Inline: False
Direct callers:
  - net/devlink/netlink.c:devlink_nl_pre_doit_port_optional
  - net/devlink/netlink.c:devlink_nl_pre_doit_port
```
**Symbols:**

```
ffffffff821079c0-ffffffff82107a0e: devlink_port_get_from_info (STB_GLOBAL)
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
In net/core/devlink.c (ffff800010c23534)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (c0d3aac4)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (c000000000d16e48)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffe00079bd8c)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff8191ba08)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff818d57b8)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff8196cb98)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff8198efe8)
Location: net/core/devlink.c:171
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_pre_doit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
