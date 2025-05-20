# Function: <code>bdi_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, struct device *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae300)
Location: mm/backing-dev.c:793
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_register_dev
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff811ae300-ffffffff811ae47d: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, struct device *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7660)
Location: mm/backing-dev.c:793
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_register_owner
  - mm/backing-dev.c:bdi_register_dev
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff811c7660-ffffffff811c77d6: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, struct device *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7780)
Location: mm/backing-dev.c:799
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_register_owner
  - mm/backing-dev.c:bdi_register_dev
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff811d7780-ffffffff811d78f6: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0d50)
Location: mm/backing-dev.c:885
Inline: False
```
**Symbols:**

```
ffffffff811e0d50-ffffffff811e0dc8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6d60)
Location: mm/backing-dev.c:900
Inline: False
```
**Symbols:**

```
ffffffff811f6d60-ffffffff811f6dd8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217ff0)
Location: mm/backing-dev.c:898
Inline: False
```
**Symbols:**

```
ffffffff81217ff0-ffffffff81218068: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122ae30)
Location: mm/backing-dev.c:901
Inline: False
```
**Symbols:**

```
ffffffff8122ae30-ffffffff8122aea8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123ab40)
Location: mm/backing-dev.c:888
Inline: False
```
**Symbols:**

```
ffffffff8123ab40-ffffffff8123abb8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248ee0)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffff81248ee0-ffffffff81248f58: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81276b20)
Location: mm/backing-dev.c:966
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81276b20-ffffffff81276b98: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281410)
Location: mm/backing-dev.c:836
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81281410-ffffffff81281488: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286b80)
Location: mm/backing-dev.c:835
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81286b80-ffffffff81286bf8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5f10)
Location: mm/backing-dev.c:909
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff812c5f10-ffffffff812c5f88: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81324640)
Location: mm/backing-dev.c:899
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81324640-ffffffff813246c4: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81398f80)
Location: mm/backing-dev.c:1022
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81398f80-ffffffff81399004: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cbee0)
Location: mm/backing-dev.c:1035
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff813cbee0-ffffffff813cbf64: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f6850)
Location: mm/backing-dev.c:1031
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff813f6850-ffffffff813f68d4: bdi_register (STB_GLOBAL)
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
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102de2c0)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffff8000102de2c0-ffff8000102de358: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503054)
Location: mm/backing-dev.c:968
Inline: False
Direct callers:
  - drivers/mtd/mtdcore.c:init_mtd
```
**Symbols:**

```
c0503054-c05030b8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039dd50)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
c00000000039dd50-c00000000039ddc0: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f657c)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffe0001f657c-ffffffe0001f65d8: bdi_register (STB_GLOBAL)
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
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241530)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffff81241530-ffffffff812415a8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234530)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffff81234530-ffffffff812345a8: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f2d0)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffff8123f2d0-ffffffff8123f348: bdi_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bdi_register(struct backing_dev_info *bdi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124ea10)
Location: mm/backing-dev.c:968
Inline: False
```
**Symbols:**

```
ffffffff8124ea10-ffffffff8124ea88: bdi_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct device *parent</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdi, parent, fmt, (anon)</code> ➡️ <code>bdi, fmt, (anon)</code>
</li>
</ul>
</details>
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
