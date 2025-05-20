# Function: <code>__fwnode_link_add</code>

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
int __fwnode_link_add(struct fwnode_handle *con, struct fwnode_handle *sup, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae27d0)
Location: drivers/base/core.c:78
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_link_add
```
**Symbols:**

```
ffffffff81ae27d0-ffffffff81ae28c3: __fwnode_link_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __fwnode_link_add(struct fwnode_handle *con, struct fwnode_handle *sup, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b306f0)
Location: drivers/base/core.c:65
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_link_add
```
**Symbols:**

```
ffffffff81b306f0-ffffffff81b307e3: __fwnode_link_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __fwnode_link_add(struct fwnode_handle *con, struct fwnode_handle *sup, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88920)
Location: drivers/base/core.c:66
Inline: False
Direct callers:
  - drivers/base/core.c:__fw_devlink_pickup_dangling_consumers
  - drivers/base/core.c:fwnode_link_add
```
**Symbols:**

```
ffffffff81b88920-ffffffff81b88a42: __fwnode_link_add (STB_LOCAL)
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
