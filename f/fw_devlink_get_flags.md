# Function: <code>fw_devlink_get_flags</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 fw_devlink_get_flags();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b4e90)
Location: drivers/base/core.c:1207
Inline: False
```
**Symbols:**

```
ffffffff817b4e90-ffffffff817b4ea1: fw_devlink_get_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 fw_devlink_get_flags();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9700)
Location: drivers/base/core.c:1480
Inline: True
Inline callers:
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff817c9700-ffffffff817c9711: fw_devlink_get_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 fw_devlink_get_flags();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817adbf0)
Location: drivers/base/core.c:1575
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff817ace70-ffffffff817ace81: fw_devlink_get_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 fw_devlink_get_flags();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818373c3)
Location: drivers/base/core.c:1590
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81836160-ffffffff81836171: fw_devlink_get_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 fw_devlink_get_flags();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81979456)
Location: drivers/base/core.c:1602
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
```
**Symbols:**

```
ffffffff81978120-ffffffff81978135: fw_devlink_get_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae562b)
Location: drivers/base/core.c:1730
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b339eb)
Location: drivers/base/core.c:1694
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_create_devlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8b319)
Location: drivers/base/core.c:1697
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_create_devlink
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
