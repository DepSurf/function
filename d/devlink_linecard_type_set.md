# Function: <code>devlink_linecard_type_set</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_linecard_type_set(struct devlink_linecard *linecard, const char *type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7e1e0)
Location: net/core/devlink.c:2230
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
```
**Symbols:**

```
ffffffff81c7e1e0-ffffffff81c7e402: devlink_linecard_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_linecard_type_set(struct devlink_linecard *linecard, const char *type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e36e00)
Location: net/core/devlink.c:2523
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_linecard_set_doit
```
**Symbols:**

```
ffffffff81e36e00-ffffffff81e37022: devlink_linecard_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_linecard_type_set(struct devlink_linecard *linecard, const char *type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82040610)
Location: net/devlink/leftover.c:1891
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_linecard_set_doit
```
**Symbols:**

```
ffffffff82040610-ffffffff82040832: devlink_linecard_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_linecard_type_set(struct devlink_linecard *linecard, const char *type, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/linecard.c (ffffffff8211a010)
Location: net/devlink/linecard.c:254
Inline: False
Direct callers:
  - net/devlink/linecard.c:devlink_nl_linecard_set_doit
```
**Symbols:**

```
ffffffff8211a010-ffffffff8211a232: devlink_linecard_type_set (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
