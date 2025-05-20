# Function: <code>bdi_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811af7d0)
Location: mm/backing-dev.c:840
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff811af7d0-ffffffff811af9d0: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c8be0)
Location: mm/backing-dev.c:854
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff811c8be0-ffffffff811c8e62: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d8d00)
Location: mm/backing-dev.c:860
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff811d8d00-ffffffff811d8f4f: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e11f0)
Location: mm/backing-dev.c:924
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_put
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff811e11f0-ffffffff811e13fc: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f7200)
Location: mm/backing-dev.c:939
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff811f7200-ffffffff811f740c: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218430)
Location: mm/backing-dev.c:937
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81218430-ffffffff81218663: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b380)
Location: mm/backing-dev.c:940
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8122b380-ffffffff8122b57b: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (0)
Location: mm/backing-dev.c:927
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8123bd9f-ffffffff8123bdb2: bdi_unregister.cold (STB_LOCAL)
ffffffff8123afd0-ffffffff8123b1b5: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812494e0)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff812494e0-ffffffff812496e0: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277850)
Location: mm/backing-dev.c:998
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81277850-ffffffff81277907: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281f00)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81281f00-ffffffff81281fb7: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286ec0)
Location: mm/backing-dev.c:867
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81286ec0-ffffffff812870cc: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6470)
Location: mm/backing-dev.c:941
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff812c6470-ffffffff812c669d: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81323100)
Location: mm/backing-dev.c:931
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81323100-ffffffff81323350: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81397910)
Location: mm/backing-dev.c:1054
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:retire_super
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81397910-ffffffff81397b60: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813ca8a0)
Location: mm/backing-dev.c:1067
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:retire_super
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff813ca8a0-ffffffff813caaf0: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f5310)
Location: mm/backing-dev.c:1063
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:retire_super
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff813f5310-ffffffff813f5560: bdi_unregister (STB_GLOBAL)
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
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102debb8)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_put
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffff8000102debb8-ffff8000102deee4: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503b88)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_put
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c0503b88-c0503d94: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039e4e0)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_put
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c00000000039e4e0-c00000000039e818: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f6a94)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffe0001f6a94-ffffffe0001f6ce0: bdi_unregister (STB_GLOBAL)
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
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241b30)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81241b30-ffffffff81241d30: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234b20)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81234b20-ffffffff81234d0e: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f8d0)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8123f8d0-ffffffff8123fad0: bdi_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f050)
Location: mm/backing-dev.c:1008
Inline: False
Direct callers:
  - mm/backing-dev.c:release_bdi
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8124f050-ffffffff8124f23e: bdi_unregister (STB_GLOBAL)
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
