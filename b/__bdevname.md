# Function: <code>__bdevname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff813cca30)
Location: block/partition-generic.c:58
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff813cca30-ffffffff813cca65: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81410d90)
Location: block/partition-generic.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff81410d90-ffffffff81410dc5: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142c120)
Location: block/partition-generic.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff8142c120-ffffffff8142c155: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814394a0)
Location: block/partition-generic.c:58
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814394a0-ffffffff814394d5: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814654b0)
Location: block/partition-generic.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/super.c:ext4_load_journal
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:handle_bad_sector
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814654b0-ffffffff814654e5: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81498e90)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff81498e90-ffffffff81498ec5: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b2fe0)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_load_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814b2fe0-ffffffff814b3015: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e1590)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814e1590-ffffffff814e15c8: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fa940)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814fa940-ffffffff814fa978: __bdevname (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fc730)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffff8000105fc730-ffff8000105fc778: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a7520)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
c07a7520-c07a7568: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c000000000795b60)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
c000000000795b60-c000000000795bbc: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe0004384b0)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffe0004384b0-ffffffe0004384f8: __bdevname (STB_GLOBAL)
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
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f2f20)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814f2f20-ffffffff814f2f58: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e3430)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814e3430-ffffffff814e3468: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814eefb0)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff814eefb0-ffffffff814eefe8: __bdevname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *__bdevname(dev_t dev, char *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81508040)
Location: block/partition-generic.c:65
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
  - fs/ext4/super.c:ext4_get_dev_journal
  - drivers/md/md.c:lock_rdev
```
**Symbols:**

```
ffffffff81508040-ffffffff81508078: __bdevname (STB_GLOBAL)
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
