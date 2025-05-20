# Function: <code>edac_device_create_instance</code>

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
In drivers/edac/edac_device_sysfs.c (ffffffff8175f4a6)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff817d1536)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff8181a2e3)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff81845ae3)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff8188889c)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff818ba84c)
Location: drivers/edac/edac_device_sysfs.c:608
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info *edac_dev, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8198ae60)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff8198ae60-ffffffff8198afe1: edac_device_create_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info *edac_dev, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8198ea70)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff8198ea70-ffffffff8198ebf1: edac_device_create_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8197302c)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81a1bd2c)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81b84d3c)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info *edac_dev, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81d23cd0)
Location: drivers/edac/edac_device_sysfs.c:609
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81d23cd0-ffffffff81d23f58: edac_device_create_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info *edac_dev, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81d8ced0)
Location: drivers/edac/edac_device_sysfs.c:611
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81d8ced0-ffffffff81d8d14e: edac_device_create_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info *edac_dev, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff81e44780)
Location: drivers/edac/edac_device_sysfs.c:611
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs
```
**Symbols:**

```
ffffffff81e44780-ffffffff81e449fe: edac_device_create_instance (STB_LOCAL)
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
In drivers/edac/edac_device_sysfs.c (ffff800010b12e40)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (c0bf0db8)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (c000000000c075d0)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffe0006ff8e2)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff818606cc)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff81827c9c)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff818afcfc)
Location: drivers/edac/edac_device_sysfs.c:608
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
In drivers/edac/edac_device_sysfs.c (ffffffff818cbf8c)
Location: drivers/edac/edac_device_sysfs.c:608
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
