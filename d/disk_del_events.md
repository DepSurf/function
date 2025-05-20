# Function: <code>disk_del_events</code>

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
In block/genhd.c (ffffffff813cb810)
Location: block/genhd.c:1832
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff8140fad0)
Location: block/genhd.c:1856
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff8142ae60)
Location: block/genhd.c:1856
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff81439070)
Location: block/genhd.c:1879
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff81465047)
Location: block/genhd.c:1963
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff81498989)
Location: block/genhd.c:1998
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814b2ad9)
Location: block/genhd.c:2023
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814e0f9b)
Location: block/genhd.c:2053
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814fa3cb)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff8155b37b)
Location: block/genhd.c:2261
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff815775bc)
Location: block/genhd.c:2132
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff8157f399)
Location: block/genhd.c:1837
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disk_del_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff815ef170)
Location: block/disk-events.c:488
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff815ef170-ffffffff815ef1c7: disk_del_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disk_del_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8169fb30)
Location: block/disk-events.c:488
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8169fb30-ffffffff8169fb9f: disk_del_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_del_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175e550)
Location: block/disk-events.c:488
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8175e550-ffffffff8175e5bf: disk_del_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_del_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179d450)
Location: block/disk-events.c:489
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8179d450-ffffffff8179d4bf: disk_del_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_del_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e0ea0)
Location: block/disk-events.c:473
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff817e0ea0-ffffffff817e0f0f: disk_del_events (STB_GLOBAL)
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
In block/genhd.c (ffff8000105fbfb4)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (c07a6ffc)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (c0000000007953ec)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffe000437f74)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814f29ab)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814e2edb)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff814eea3b)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
In block/genhd.c (ffffffff81507adb)
Location: block/genhd.c:2062
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
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
