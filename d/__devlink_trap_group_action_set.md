# Function: <code>__devlink_trap_group_action_set</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d64e)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81a52f92)
Location: net/core/devlink.c:6322
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81a590b0)
Location: net/core/devlink.c:7168
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
```
**Symbols:**

```
ffffffff81a590b0-ffffffff81a591a5: __devlink_trap_group_action_set.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a3c515)
Location: net/core/devlink.c:7371
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81af27f5)
Location: net/core/devlink.c:8058
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81c767a8)
Location: net/core/devlink.c:8551
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81e2efb8)
Location: net/core/devlink.c:9070
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82030ed8)
Location: net/devlink/leftover.c:5917
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82117298)
Location: net/devlink/trap.c:586
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
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
In net/core/devlink.c (ffff800010c251b8)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (c0d3a418)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (c000000000d18ed4)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffe00079d6a4)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff8191d4be)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff818d726e)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff8196e64e)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
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
In net/core/devlink.c (ffffffff81990afe)
Location: net/core/devlink.c:5712
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
```
</details>
</li>
</ul>

## Differences
