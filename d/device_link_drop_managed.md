# Function: <code>device_link_drop_managed</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb701)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3610)
Location: drivers/base/core.c:846
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817b3610-ffffffff817b3656: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c81b0)
Location: drivers/base/core.c:1107
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
```
**Symbols:**

```
ffffffff817c81b0-ffffffff817c8202: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab6c0)
Location: drivers/base/core.c:1144
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff817ab6c0-ffffffff817ab712: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834900)
Location: drivers/base/core.c:1159
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff81834900-ffffffff81834952: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819762c0)
Location: drivers/base/core.c:1171
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff819762c0-ffffffff81976336: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae23a0)
Location: drivers/base/core.c:1278
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff81ae23a0-ffffffff81ae2416: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b302c0)
Location: drivers/base/core.c:1217
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff81b302c0-ffffffff81b30336: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87ac0)
Location: drivers/base/core.c:1220
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_force_bind
```
**Symbols:**

```
ffffffff81b87ac0-ffffffff81b87b36: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e2da0)
Location: drivers/base/core.c:638
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffff8000108e2da0-ffff8000108e2df4: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d1978)
Location: drivers/base/core.c:638
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
c09d1978-c09d19c4: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_link_drop_managed(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000977a10)
Location: drivers/base/core.c:638
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
c000000000977a10-c000000000977a64: device_link_drop_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a9f6)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0ef1)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c1a1)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef3c1)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709c01)
Location: drivers/base/core.c:638
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
</details>
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
<b>Arch</b>
<ul>
</ul>
