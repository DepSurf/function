# Function: <code>dm_emulate_zone_append</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a06187)
Location: drivers/md/dm-core.h:157
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
```
```
In drivers/md/dm.c (ffffffff81a0a708)
Location: drivers/md/dm-core.h:157
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6dde7)
Location: drivers/md/dm-core.h:169
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
```
```
In drivers/md/dm.c (ffffffff81b7241b)
Location: drivers/md/dm-core.h:169
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d0a2ef)
Location: drivers/md/dm-core.h:179
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
```
```
In drivers/md/dm.c (ffffffff81d0f18e)
Location: drivers/md/dm-core.h:179
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d7342f)
Location: drivers/md/dm-core.h:180
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
```
```
In drivers/md/dm.c (ffffffff81d78552)
Location: drivers/md/dm-core.h:180
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e2a51f)
Location: drivers/md/dm-core.h:182
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
```
```
In drivers/md/dm.c (ffffffff81e2f794)
Location: drivers/md/dm-core.h:182
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
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
