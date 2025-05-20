# Function: <code>auxiliary_match_id</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:20
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff817d8950-ffffffff817d89fd: auxiliary_match_id (STB_LOCAL)
ffffffff81c0e617-ffffffff81c0e62f: auxiliary_match_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:20
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff817bca90-ffffffff817bcb3d: auxiliary_match_id (STB_LOCAL)
ffffffff81c00a2a-ffffffff81c00a42: auxiliary_match_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:20
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff81846de0-ffffffff81846e8d: auxiliary_match_id (STB_LOCAL)
ffffffff81d034b4-ffffffff81d034cc: auxiliary_match_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:161
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff8198b7c0-ffffffff8198b88a: auxiliary_match_id (STB_LOCAL)
ffffffff81ecbc5b-ffffffff81ecbc73: auxiliary_match_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afad80)
Location: drivers/base/auxiliary.c:161
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff81afad80-ffffffff81afae5a: auxiliary_match_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b49170)
Location: drivers/base/auxiliary.c:161
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff81b49170-ffffffff81b4924a: auxiliary_match_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct auxiliary_device_id *auxiliary_match_id(const struct auxiliary_device_id *id, const struct auxiliary_device *auxdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba1560)
Location: drivers/base/auxiliary.c:161
Inline: False
Direct callers:
  - drivers/base/auxiliary.c:auxiliary_bus_probe
  - drivers/base/auxiliary.c:auxiliary_match
```
**Symbols:**

```
ffffffff81ba1560-ffffffff81ba163a: auxiliary_match_id (STB_LOCAL)
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
