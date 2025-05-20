# Function: <code>disk_alloc_events</code>

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
In block/genhd.c (ffffffff813cb02f)
Location: block/genhd.c:1787
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
In block/genhd.c (ffffffff8140f2fb)
Location: block/genhd.c:1811
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
In block/genhd.c (ffffffff8142a69b)
Location: block/genhd.c:1811
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
In block/genhd.c (ffffffff8143895f)
Location: block/genhd.c:1834
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
In block/genhd.c (ffffffff814648e8)
Location: block/genhd.c:1918
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
In block/genhd.c (ffffffff8149820b)
Location: block/genhd.c:1953
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
In block/genhd.c (ffffffff814b2335)
Location: block/genhd.c:1978
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
In block/genhd.c (ffffffff814e075b)
Location: block/genhd.c:2008
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
In block/genhd.c (ffffffff814f9bbe)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffff8155aa6e)
Location: block/genhd.c:2216
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
In block/genhd.c (ffffffff81576dc5)
Location: block/genhd.c:2087
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
In block/genhd.c (ffffffff8157ed4b)
Location: block/genhd.c:1792
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int disk_alloc_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/disk-events.c (0)
Location: block/disk-events.c:447
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81cd9bcf-ffffffff81cd9beb: disk_alloc_events.cold (STB_LOCAL)
ffffffff815ef010-ffffffff815ef0f9: disk_alloc_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int disk_alloc_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/disk-events.c (0)
Location: block/disk-events.c:447
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81e8d65f-ffffffff81e8d67a: disk_alloc_events.cold (STB_LOCAL)
ffffffff8169f9c0-ffffffff8169fab0: disk_alloc_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int disk_alloc_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175e3a0)
Location: block/disk-events.c:447
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8175e3a0-ffffffff8175e4ab: disk_alloc_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int disk_alloc_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179d2a0)
Location: block/disk-events.c:448
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8179d2a0-ffffffff8179d3ab: disk_alloc_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int disk_alloc_events(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e0cc0)
Location: block/disk-events.c:432
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817e0cc0-ffffffff817e0dfa: disk_alloc_events (STB_GLOBAL)
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
In block/genhd.c (ffff8000105fb6d4)
Location: block/genhd.c:2017
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
In block/genhd.c (c07a66a0)
Location: block/genhd.c:2017
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
In block/genhd.c (c0000000007948e4)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffe000437780)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffff814f219e)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffff814e26ce)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffff814ee22e)
Location: block/genhd.c:2017
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
In block/genhd.c (ffffffff815072be)
Location: block/genhd.c:2017
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
