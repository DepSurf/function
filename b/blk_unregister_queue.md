# Function: <code>blk_unregister_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff813bd370)
Location: block/blk-sysfs.c:675
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff813bd370-ffffffff813bd3fd: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814012a0)
Location: block/blk-sysfs.c:724
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814012a0-ffffffff8140132d: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8141aee0)
Location: block/blk-sysfs.c:915
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8141aee0-ffffffff8141af78: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81428ef0)
Location: block/blk-sysfs.c:927
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81428ef0-ffffffff81428fab: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81453fc0)
Location: block/blk-sysfs.c:925
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81453fc0-ffffffff81454092: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814873e0)
Location: block/blk-sysfs.c:950
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814873e0-ffffffff814874dc: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814a1610)
Location: block/blk-sysfs.c:978
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814a1610-ffffffff814a16e8: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-sysfs.c (0)
Location: block/blk-sysfs.c:1024
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814cf811-ffffffff814cf824: blk_unregister_queue.cold (STB_LOCAL)
ffffffff814cf730-ffffffff814cf7f8: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814e8a90)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814e8a90-ffffffff814e8b85: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81547a00)
Location: block/blk-sysfs.c:1034
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81547a00-ffffffff81547af5: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81563730)
Location: block/blk-sysfs.c:934
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81563730-ffffffff8156382d: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8156bea0)
Location: block/blk-sysfs.c:952
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8156bea0-ffffffff8156bf9d: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815d0320)
Location: block/blk-sysfs.c:930
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815d0320-ffffffff815d041d: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8167bac0)
Location: block/blk-sysfs.c:904
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8167bac0-ffffffff8167bc25: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81738330)
Location: block/blk-sysfs.c:866
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81738330-ffffffff81738478: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81774900)
Location: block/blk-sysfs.c:872
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81774900-ffffffff81774a4b: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817b6c80)
Location: block/blk-sysfs.c:869
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817b6c80-ffffffff817b6dc8: blk_unregister_queue (STB_GLOBAL)
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
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffff8000105e6a18)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffff8000105e6a18-ffff8000105e6b10: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c0793788)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c0793788-c0793874: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c00000000077b210)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c00000000077b210-c00000000077b36c: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffe000427a66)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffe000427a66-ffffffe000427b4c: blk_unregister_queue (STB_GLOBAL)
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
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814e1070)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814e1070-ffffffff814e1165: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814d1a00)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814d1a00-ffffffff814d1af5: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814dd100)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814dd100-ffffffff814dd1f5: blk_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_unregister_queue(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814f5f60)
Location: block/blk-sysfs.c:1029
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff814f5f60-ffffffff814f6055: blk_unregister_queue (STB_GLOBAL)
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
