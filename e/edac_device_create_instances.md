# Function: <code>edac_device_create_instances</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8175f48d)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff817d151d)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int edac_device_create_instances(struct edac_device_ctl_info *edac_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81972ff0)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81972ff0-ffffffff8197335c: edac_device_create_instances (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int edac_device_create_instances(struct edac_device_ctl_info *edac_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81a1bcf0)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81a1bcf0-ffffffff81a1c05c: edac_device_create_instances (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int edac_device_create_instances(struct edac_device_ctl_info *edac_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81b84d00)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81b84d00-ffffffff81b850a1: edac_device_create_instances (STB_LOCAL)
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
In drivers/edac/edac_device_sysfs.c (ffffffff81d24138)
Location: drivers/edac/edac_device_sysfs.c:700
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (ffffffff81d8d358)
Location: drivers/edac/edac_device_sysfs.c:702
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (ffffffff81e44c08)
Location: drivers/edac/edac_device_sysfs.c:702
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (ffffffe0006ff8dc)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
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
In drivers/edac/edac_device_sysfs.c (0)
Location: drivers/edac/edac_device_sysfs.c:699
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
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
</ul>
