# Function: <code>fw_devlink_relax_link</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ae24a)
Location: drivers/base/core.c:1609
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff817aae80-ffffffff817aaee4: fw_devlink_relax_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8183745f)
Location: drivers/base/core.c:1624
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff81833fb0-ffffffff81834011: fw_devlink_relax_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819794ef)
Location: drivers/base/core.c:1636
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff819758a0-ffffffff8197591d: fw_devlink_relax_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae5fca)
Location: drivers/base/core.c:1767
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff81ae1450-ffffffff81ae14d3: fw_devlink_relax_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b34388)
Location: drivers/base/core.c:1731
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff81b2f6b0-ffffffff81b2f745: fw_devlink_relax_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fw_devlink_relax_link(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8bd58)
Location: drivers/base/core.c:1734
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_no_driver
```
**Symbols:**

```
ffffffff81b86eb0-ffffffff81b86f45: fw_devlink_relax_link (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
