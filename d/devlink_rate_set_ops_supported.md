# Function: <code>devlink_rate_set_ops_supported</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops *ops, struct genl_info *info, enum devlink_rate_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afd795)
Location: net/core/devlink.c:1713
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81af0010-ffffffff81af01bb: devlink_rate_set_ops_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops *ops, struct genl_info *info, enum devlink_rate_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c83ac5)
Location: net/core/devlink.c:1916
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81c735f0-ffffffff81c73797: devlink_rate_set_ops_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops *ops, struct genl_info *info, enum devlink_rate_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2bc80)
Location: net/core/devlink.c:2191
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
  - net/core/devlink.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff81e2bc80-ffffffff81e2bf91: devlink_rate_set_ops_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops *ops, struct genl_info *info, enum devlink_rate_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202fb80)
Location: net/devlink/leftover.c:1563
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
  - net/devlink/leftover.c:devlink_nl_cmd_rate_set_doit
```
**Symbols:**

```
ffffffff8202fb80-ffffffff8202fe91: devlink_rate_set_ops_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops *ops, struct genl_info *info, enum devlink_rate_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/rate.c (ffffffff82117c20)
Location: net/devlink/rate.c:394
Inline: False
Direct callers:
  - net/devlink/rate.c:devlink_nl_rate_new_doit
  - net/devlink/rate.c:devlink_nl_rate_set_doit
```
**Symbols:**

```
ffffffff82117c20-ffffffff82117f31: devlink_rate_set_ops_supported (STB_LOCAL)
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
