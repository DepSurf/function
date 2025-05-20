# Function: <code>__fw_devlink_relax_cycles</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __fw_devlink_relax_cycles(struct device *con, struct fwnode_handle *sup_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1540)
Location: drivers/base/core.c:1919
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81ae1540-ffffffff81ae17b9: __fw_devlink_relax_cycles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __fw_devlink_relax_cycles(struct device *con, struct fwnode_handle *sup_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b31560)
Location: drivers/base/core.c:1921
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81b31560-ffffffff81b31816: __fw_devlink_relax_cycles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __fw_devlink_relax_cycles(struct device *con, struct fwnode_handle *sup_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88d90)
Location: drivers/base/core.c:1924
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
```
**Symbols:**

```
ffffffff81b88d90-ffffffff81b890ba: __fw_devlink_relax_cycles (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
