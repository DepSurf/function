# Function: <code>devlink_port_get_from_attrs</code>

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
Location: net/core/devlink.c:152
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:165
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
In net/core/devlink.c (ffffffff81a59e6e)
Location: net/core/devlink.c:169
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
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
In net/core/devlink.c (ffffffff81a3cfbe)
Location: net/core/devlink.c:172
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
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
In net/core/devlink.c (ffffffff81af52be)
Location: net/core/devlink.c:173
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81c7979d)
Location: net/core/devlink.c:324
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_pre_doit
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
In net/core/devlink.c (ffffffff81e325ad)
Location: net/core/devlink.c:393
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct devlink_port *devlink_port_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82041178)
Location: net/devlink/leftover.c:159
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_rate_get_from_info
  - net/devlink/leftover.c:devlink_port_get_from_info
Direct callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
```
**Symbols:**

```
ffffffff82041050-ffffffff8204109a: devlink_port_get_from_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct devlink_port *devlink_port_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff821079c5)
Location: net/devlink/port.c:32
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_get_from_info
Direct callers:
  - net/devlink/health.c:devlink_health_reporter_get_from_attrs
```
**Symbols:**

```
ffffffff82107960-ffffffff821079aa: devlink_port_get_from_attrs (STB_GLOBAL)
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
Location: net/core/devlink.c:156
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
