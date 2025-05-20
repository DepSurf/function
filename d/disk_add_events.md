# Function: <code>disk_add_events</code>

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
In block/genhd.c (ffffffff813cb1bd)
Location: block/genhd.c:1811
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
In block/genhd.c (ffffffff8140f484)
Location: block/genhd.c:1835
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
In block/genhd.c (ffffffff8142a821)
Location: block/genhd.c:1835
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
In block/genhd.c (ffffffff81438ae6)
Location: block/genhd.c:1858
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
In block/genhd.c (ffffffff81464a0e)
Location: block/genhd.c:1942
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
In block/genhd.c (ffffffff81498434)
Location: block/genhd.c:1977
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
In block/genhd.c (ffffffff814b2571)
Location: block/genhd.c:2002
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
In block/genhd.c (ffffffff814e07f7)
Location: block/genhd.c:2032
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
In block/genhd.c (ffffffff814f9d5e)
Location: block/genhd.c:2041
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff8155aad3)
Location: block/genhd.c:2240
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff81576e19)
Location: block/genhd.c:2111
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
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
In block/genhd.c (ffffffff8157ed9f)
Location: block/genhd.c:1816
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disk_add_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff815ef100)
Location: block/disk-events.c:472
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815ef100-ffffffff815ef168: disk_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disk_add_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8169fab0)
Location: block/disk-events.c:472
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8169fab0-ffffffff8169fb2e: disk_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_add_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175e4c0)
Location: block/disk-events.c:472
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8175e4c0-ffffffff8175e53e: disk_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_add_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179d3c0)
Location: block/disk-events.c:473
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8179d3c0-ffffffff8179d43e: disk_add_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_add_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e0e10)
Location: block/disk-events.c:457
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817e0e10-ffffffff817e0e8e: disk_add_events (STB_GLOBAL)
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
In block/genhd.c (ffff8000105fb834)
Location: block/genhd.c:2041
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
In block/genhd.c (c07a684c)
Location: block/genhd.c:2041
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
In block/genhd.c (c000000000794ad8)
Location: block/genhd.c:2041
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
In block/genhd.c (ffffffe0004378fe)
Location: block/genhd.c:2041
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
In block/genhd.c (ffffffff814f233e)
Location: block/genhd.c:2041
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
In block/genhd.c (ffffffff814e286e)
Location: block/genhd.c:2041
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
In block/genhd.c (ffffffff814ee3ce)
Location: block/genhd.c:2041
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
In block/genhd.c (ffffffff81507468)
Location: block/genhd.c:2041
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
