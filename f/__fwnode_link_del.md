# Function: <code>__fwnode_link_del</code>

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
void __fwnode_link_del(struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81835dad)
Location: drivers/base/core.c:112
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fwnode_links_purge
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff818328b0-ffffffff81832934: __fwnode_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __fwnode_link_del(struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81977d1c)
Location: drivers/base/core.c:113
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_bound
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fwnode_links_purge
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff81974060-ffffffff819740e9: __fwnode_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __fwnode_link_del(struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81adf740)
Location: drivers/base/core.c:123
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_links_purge
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff81adf740-ffffffff81adf7c9: __fwnode_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fwnode_link_del(struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2d970)
Location: drivers/base/core.c:110
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_links_purge
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff81b2d970-ffffffff81b2d9f9: __fwnode_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fwnode_link_del(struct fwnode_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b85170)
Location: drivers/base/core.c:111
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_links_purge
  - drivers/base/core.c:fwnode_links_purge
```
**Symbols:**

```
ffffffff81b85170-ffffffff81b851f9: __fwnode_link_del (STB_LOCAL)
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
