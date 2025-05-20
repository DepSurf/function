# Function: <code>__fw_devlink_pickup_dangling_consumers</code>

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
void __fw_devlink_pickup_dangling_consumers(struct fwnode_handle *fwnode, struct fwnode_handle *new_sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae28e0)
Location: drivers/base/core.c:235
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81ae28e0-ffffffff81ae29b4: __fw_devlink_pickup_dangling_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fw_devlink_pickup_dangling_consumers(struct fwnode_handle *fwnode, struct fwnode_handle *new_sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30800)
Location: drivers/base/core.c:222
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81b30800-ffffffff81b308d4: __fw_devlink_pickup_dangling_consumers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fw_devlink_pickup_dangling_consumers(struct fwnode_handle *fwnode, struct fwnode_handle *new_sup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88a60)
Location: drivers/base/core.c:223
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
```
**Symbols:**

```
ffffffff81b88a60-ffffffff81b88b34: __fw_devlink_pickup_dangling_consumers (STB_LOCAL)
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
