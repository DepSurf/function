# Function: <code>register_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813cb10a)
Location: block/genhd.c:508
Inline: True
Inline callers:
  - block/genhd.c:add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140f412)
Location: block/genhd.c:509
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142a7af)
Location: block/genhd.c:509
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81438a73)
Location: block/genhd.c:510
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In block/genhd.c (ffffffff814649c5)
Location: block/genhd.c:555
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
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
In block/genhd.c (ffffffff814982dc)
Location: block/genhd.c:570
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814b23fd)
Location: block/genhd.c:583
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814e078e)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814f9bf1)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void register_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155a1f0)
Location: block/genhd.c:682
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8155a1f0-ffffffff8155a3f4: register_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void register_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575fc0)
Location: block/genhd.c:621
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81575fc0-ffffffff815761c1: register_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void register_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157de40)
Location: block/genhd.c:430
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8157de40-ffffffff8157dfc9: register_disk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/genhd.c (ffff8000105fb6fc)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (c07a66d0)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (c000000000794918)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffe0004377ba)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814f21d1)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814e2701)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff814ee261)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff815072f1)
Location: block/genhd.c:596
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
</ul>
