# Function: <code>disk_release_events</code>

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
In block/genhd.c (ffffffff813cac3d)
Location: block/genhd.c:1846
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff8140ef0d)
Location: block/genhd.c:1870
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff8142a2ad)
Location: block/genhd.c:1870
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff81438594)
Location: block/genhd.c:1893
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff81463ff4)
Location: block/genhd.c:1977
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814978f4)
Location: block/genhd.c:2012
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814b1814)
Location: block/genhd.c:2037
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814dfbf4)
Location: block/genhd.c:2066
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814f9024)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff81559d5c)
Location: block/genhd.c:2274
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff81576425)
Location: block/genhd.c:2145
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff8157e066)
Location: block/genhd.c:1850
Inline: True
Inline callers:
  - block/genhd.c:disk_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disk_release_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff815ef1d0)
Location: block/disk-events.c:499
Inline: False
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff815ef1d0-ffffffff815ef1f4: disk_release_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disk_release_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8169fba0)
Location: block/disk-events.c:499
Inline: False
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff8169fba0-ffffffff8169fbca: disk_release_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_release_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175e5d0)
Location: block/disk-events.c:499
Inline: False
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff8175e5d0-ffffffff8175e5fa: disk_release_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_release_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179d4d0)
Location: block/disk-events.c:500
Inline: False
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff8179d4d0-ffffffff8179d4fa: disk_release_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_release_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e0f20)
Location: block/disk-events.c:484
Inline: False
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff817e0f20-ffffffff817e0f4a: disk_release_events (STB_GLOBAL)
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
In block/genhd.c (ffff8000105fa730)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (c07a55e4)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (c000000000793684)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffe000436bac)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814f1604)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814e1b44)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff814ed694)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
In block/genhd.c (ffffffff815068a4)
Location: block/genhd.c:2075
Inline: True
Inline callers:
  - block/genhd.c:disk_release
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
