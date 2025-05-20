# Function: <code>devlink_nl_rate_set</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_rate_set(struct devlink_rate *devlink_rate, const struct devlink_ops *ops, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af2230)
Location: net/core/devlink.c:1668
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81af2230-ffffffff81af239f: devlink_nl_rate_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_rate_set(struct devlink_rate *devlink_rate, const struct devlink_ops *ops, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79f90)
Location: net/core/devlink.c:1871
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81c79f90-ffffffff81c7a119: devlink_nl_rate_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_rate_set(struct devlink_rate *devlink_rate, const struct devlink_ops *ops, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e34590)
Location: net/core/devlink.c:2116
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81e34590-ffffffff81e347e1: devlink_nl_rate_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_rate_set(struct devlink_rate *devlink_rate, const struct devlink_ops *ops, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82034230)
Location: net/devlink/leftover.c:1488
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff82034230-ffffffff82034481: devlink_nl_rate_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_rate_set(struct devlink_rate *devlink_rate, const struct devlink_ops *ops, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/rate.c (ffffffff82118550)
Location: net/devlink/rate.c:319
Inline: False
Direct callers:
  - net/devlink/rate.c:devlink_nl_rate_new_doit
  - net/devlink/rate.c:devlink_nl_rate_set_doit
```
**Symbols:**

```
ffffffff82118550-ffffffff821187a1: devlink_nl_rate_set (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
