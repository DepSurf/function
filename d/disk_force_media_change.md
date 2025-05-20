# Function: <code>disk_force_media_change</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool disk_force_media_change(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/disk-events.c (ffffffff815eeb74)
Location: block/disk-events.c:303
Inline: True
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81cd9b9d-ffffffff81cd9bb2: disk_force_media_change.cold (STB_LOCAL)
ffffffff815eeb50-ffffffff815eeb99: disk_force_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool disk_force_media_change(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/disk-events.c (ffffffff8169f36c)
Location: block/disk-events.c:303
Inline: True
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81e8d62d-ffffffff81e8d642: disk_force_media_change.cold (STB_LOCAL)
ffffffff8169f340-ffffffff8169f399: disk_force_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool disk_force_media_change(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175dc50)
Location: block/disk-events.c:303
Inline: True
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff8175dc50-ffffffff8175dcba: disk_force_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool disk_force_media_change(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179cb50)
Location: block/disk-events.c:303
Inline: True
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff8179cb50-ffffffff8179cbc2: disk_force_media_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_force_media_change(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e04f0)
Location: block/disk-events.c:294
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff817e04f0-ffffffff817e0533: disk_force_media_change (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int events</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
