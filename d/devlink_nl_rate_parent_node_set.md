# Function: <code>devlink_nl_rate_parent_node_set</code>

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
int devlink_nl_rate_parent_node_set(struct devlink_rate *devlink_rate, struct genl_info *info, struct nlattr *nla_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af1f30)
Location: net/core/devlink.c:1605
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_rate_set
```
**Symbols:**

```
ffffffff81af1f30-ffffffff81af222e: devlink_nl_rate_parent_node_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_rate_parent_node_set(struct devlink_rate *devlink_rate, struct genl_info *info, struct nlattr *nla_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c79c90)
Location: net/core/devlink.c:1808
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_rate_set
```
**Symbols:**

```
ffffffff81c79c90-ffffffff81c79f82: devlink_nl_rate_parent_node_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_rate_parent_node_set(struct devlink_rate *devlink_rate, struct genl_info *info, struct nlattr *nla_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e34290)
Location: net/core/devlink.c:2051
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_rate_set
```
**Symbols:**

```
ffffffff81e34290-ffffffff81e34578: devlink_nl_rate_parent_node_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_rate_parent_node_set(struct devlink_rate *devlink_rate, struct genl_info *info, struct nlattr *nla_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82033f30)
Location: net/devlink/leftover.c:1423
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_rate_set
```
**Symbols:**

```
ffffffff82033f30-ffffffff82034218: devlink_nl_rate_parent_node_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_rate_parent_node_set(struct devlink_rate *devlink_rate, struct genl_info *info, struct nlattr *nla_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/rate.c (ffffffff82118250)
Location: net/devlink/rate.c:254
Inline: False
Direct callers:
  - net/devlink/rate.c:devlink_nl_rate_set
```
**Symbols:**

```
ffffffff82118250-ffffffff82118538: devlink_nl_rate_parent_node_set (STB_LOCAL)
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
