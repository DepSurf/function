# Function: <code>edac_device_create_block</code>

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
In drivers/edac/edac_device_sysfs.c (ffffffff8175f555)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff817d15e5)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff8181a37f)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff81845b7f)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff81888937)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff818ba8e7)
Location: drivers/edac/edac_device_sysfs.c:507
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
int edac_device_create_block(struct edac_device_ctl_info *edac_dev, struct edac_device_instance *instance, struct edac_device_block *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8198ad50)
Location: drivers/edac/edac_device_sysfs.c:508
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
**Symbols:**

```
ffffffff8198ad50-ffffffff8198ae54: edac_device_create_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int edac_device_create_block(struct edac_device_ctl_info *edac_dev, struct edac_device_instance *instance, struct edac_device_block *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device_sysfs.c (ffffffff8198e960)
Location: drivers/edac/edac_device_sysfs.c:508
Inline: False
Direct callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
```
**Symbols:**

```
ffffffff8198e960-ffffffff8198ea64: edac_device_create_block (STB_LOCAL)
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
In drivers/edac/edac_device_sysfs.c (ffffffff819730f3)
Location: drivers/edac/edac_device_sysfs.c:508
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
In drivers/edac/edac_device_sysfs.c (ffffffff81a1bdf3)
Location: drivers/edac/edac_device_sysfs.c:508
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
In drivers/edac/edac_device_sysfs.c (ffffffff81b84e17)
Location: drivers/edac/edac_device_sysfs.c:508
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instances
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
In drivers/edac/edac_device_sysfs.c (ffffffff81d23db9)
Location: drivers/edac/edac_device_sysfs.c:508
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
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
In drivers/edac/edac_device_sysfs.c (ffffffff81d8cfb9)
Location: drivers/edac/edac_device_sysfs.c:510
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
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
In drivers/edac/edac_device_sysfs.c (ffffffff81e44869)
Location: drivers/edac/edac_device_sysfs.c:510
Inline: True
Inline callers:
  - drivers/edac/edac_device_sysfs.c:edac_device_create_instance
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
In drivers/edac/edac_device_sysfs.c (ffff800010b12eb8)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (c0bf0e40)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (c000000000c07670)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffe0006ff94e)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff81860767)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff81827d37)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff818afd97)
Location: drivers/edac/edac_device_sysfs.c:507
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
In drivers/edac/edac_device_sysfs.c (ffffffff818cc027)
Location: drivers/edac/edac_device_sysfs.c:507
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
</ul>
