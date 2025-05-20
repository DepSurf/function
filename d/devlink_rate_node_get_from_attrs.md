# Function: <code>devlink_rate_node_get_from_attrs</code>

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
struct devlink_rate *devlink_rate_node_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af37b0)
Location: net/core/devlink.c:233
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81af37b0-ffffffff81af3873: devlink_rate_node_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_rate *devlink_rate_node_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c77a10)
Location: net/core/devlink.c:384
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_pre_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81c77a10-ffffffff81c77ae8: devlink_rate_node_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_rate *devlink_rate_node_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e30fe0)
Location: net/core/devlink.c:453
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_pre_doit
```
**Symbols:**

```
ffffffff81e30fe0-ffffffff81e310b8: devlink_rate_node_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_rate *devlink_rate_node_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82033a50)
Location: net/devlink/leftover.c:219
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
  - net/devlink/leftover.c:devlink_rate_get_from_info
```
**Symbols:**

```
ffffffff82033a50-ffffffff82033b28: devlink_rate_node_get_from_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_rate *devlink_rate_node_get_from_attrs(struct devlink *devlink, struct nlattr **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/rate.c (ffffffff821180f0)
Location: net/devlink/rate.c:48
Inline: False
Direct callers:
  - net/devlink/rate.c:devlink_nl_rate_del_doit
  - net/devlink/rate.c:devlink_nl_rate_new_doit
```
**Symbols:**

```
ffffffff821180f0-ffffffff821181c8: devlink_rate_node_get_from_attrs (STB_LOCAL)
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
