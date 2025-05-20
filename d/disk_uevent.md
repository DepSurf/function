# Function: <code>disk_uevent</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157d480)
Location: block/genhd.c:396
Inline: False
Direct callers:
  - block/genhd.c:register_disk
```
**Symbols:**

```
ffffffff8157d480-ffffffff8157d54e: disk_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e28d0)
Location: block/genhd.c:350
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815e28d0-ffffffff815e299e: disk_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81691900)
Location: block/genhd.c:361
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81691900-ffffffff816919ea: disk_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817504b0)
Location: block/genhd.c:338
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817504b0-ffffffff8175059a: disk_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178c770)
Location: block/genhd.c:322
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8178c770-ffffffff8178c85a: disk_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_uevent(struct gendisk *disk, enum kobject_action action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cef40)
Location: block/genhd.c:322
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817cef40-ffffffff817cf02a: disk_uevent (STB_GLOBAL)
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
