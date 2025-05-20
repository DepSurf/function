# Function: <code>blk_register_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff813bd210)
Location: block/blk-sysfs.c:621
Inline: False
Direct callers:
  - block/genhd.c:add_disk
```
**Symbols:**

```
ffffffff813bd210-ffffffff813bd363: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81401140)
Location: block/blk-sysfs.c:670
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81401140-ffffffff81401293: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8141ad70)
Location: block/blk-sysfs.c:859
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8141ad70-ffffffff8141aedc: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81428d10)
Location: block/blk-sysfs.c:858
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81428d10-ffffffff81428ee2: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81453de0)
Location: block/blk-sysfs.c:856
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81453de0-ffffffff81453fb2: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81486d60)
Location: block/blk-sysfs.c:872
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81486d60-ffffffff81486f5d: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814a1380)
Location: block/blk-sysfs.c:901
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814a1380-ffffffff814a153b: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-sysfs.c (0)
Location: block/blk-sysfs.c:939
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814cf7f8-ffffffff814cf811: blk_register_queue.cold (STB_LOCAL)
ffffffff814ce430-ffffffff814ce609: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814e7740)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814e7740-ffffffff814e7972: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81546600)
Location: block/blk-sysfs.c:943
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81546600-ffffffff81546835: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81562250)
Location: block/blk-sysfs.c:838
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81562250-ffffffff8156249e: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8156a9b0)
Location: block/blk-sysfs.c:856
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8156a9b0-ffffffff8156abf9: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815d0130)
Location: block/blk-sysfs.c:843
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815d0130-ffffffff815d031b: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8167b880)
Location: block/blk-sysfs.c:805
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8167b880-ffffffff8167bab5: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81738100)
Location: block/blk-sysfs.c:781
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81738100-ffffffff8173831c: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817746c0)
Location: block/blk-sysfs.c:787
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817746c0-ffffffff817748e2: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817b6a50)
Location: block/blk-sysfs.c:784
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817b6a50-ffffffff817b6c6f: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffff8000105e5268)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffff8000105e5268-ffff8000105e54b0: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c079227c)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
c079227c-c07924dc: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c000000000779210)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
c000000000779210-c000000000779530: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffe000426660)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffe000426660-ffffffe000426890: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814dfd20)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814dfd20-ffffffff814dff52: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814d06c0)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814d06c0-ffffffff814d08f2: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814dbdb0)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814dbdb0-ffffffff814dbfe2: blk_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_register_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814f4c20)
Location: block/blk-sysfs.c:938
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814f4c20-ffffffff814f4e52: blk_register_queue (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
