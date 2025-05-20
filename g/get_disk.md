# Function: <code>get_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kobject *get_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813ca780)
Location: block/genhd.c:1305
Inline: False
Direct callers:
  - block/genhd.c:exact_lock
  - drivers/block/brd.c:brd_probe
  - drivers/block/brd.c:brd_probe
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff813ca780-ffffffff813ca7d5: get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kobject *get_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140ea30)
Location: block/genhd.c:1334
Inline: False
Direct callers:
  - block/genhd.c:exact_lock
  - drivers/block/brd.c:brd_probe
  - drivers/block/brd.c:brd_probe
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff8140ea30-ffffffff8140ea9e: get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kobject *get_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81429dd0)
Location: block/genhd.c:1334
Inline: False
Direct callers:
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff81429dd0-ffffffff81429e3e: get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kobject *get_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814380e0)
Location: block/genhd.c:1357
Inline: False
Direct callers:
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff814380e0-ffffffff81438147: get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kobject *get_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463b10)
Location: block/genhd.c:1441
Inline: False
Direct callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:exact_lock
  - drivers/block/loop.c:loop_probe
```
**Symbols:**

```
ffffffff81463b10-ffffffff81463b77: get_disk (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
