# Function: <code>fat_read_static_bpb</code>

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
In fs/fat/inode.c (ffffffff812fd08a)
Location: fs/fat/inode.c:1417
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81330d24)
Location: fs/fat/inode.c:1507
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81346a74)
Location: fs/fat/inode.c:1517
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8135b477)
Location: fs/fat/inode.c:1517
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8138017a)
Location: fs/fat/inode.c:1517
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813aefcb)
Location: fs/fat/inode.c:1539
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813c8259)
Location: fs/fat/inode.c:1531
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813f2d84)
Location: fs/fat/inode.c:1526
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8140cc84)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1534
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81459530-ffffffff814596a7: fat_read_static_bpb (STB_LOCAL)
ffffffff8145ba87-ffffffff8145bb04: fat_read_static_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1533
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81475880-ffffffff814759f7: fat_read_static_bpb (STB_LOCAL)
ffffffff81bed9ce-ffffffff81beda4b: fat_read_static_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1533
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8147b2f0-ffffffff8147b460: fat_read_static_bpb (STB_LOCAL)
ffffffff81bdfad2-ffffffff81bdfb4f: fat_read_static_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1534
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814d2910-ffffffff814d2ae7: fat_read_static_bpb (STB_LOCAL)
ffffffff81ccffbb-ffffffff81cd0044: fat_read_static_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1538
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8155f950-ffffffff8155fb2c: fat_read_static_bpb (STB_LOCAL)
ffffffff81e831f9-ffffffff81e83278: fat_read_static_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81601d00)
Location: fs/fat/inode.c:1533
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81601d00-ffffffff81601f4d: fat_read_static_bpb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81639c00)
Location: fs/fat/inode.c:1533
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81639c00-ffffffff81639e4d: fat_read_static_bpb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_read_static_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff816730f0)
Location: fs/fat/inode.c:1541
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff816730f0-ffffffff8167333d: fat_read_static_bpb (STB_LOCAL)
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
In fs/fat/inode.c (ffff8000104eda8c)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (c06ab710)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (c00000000062c6d8)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffe00035d85e)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81405264)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813f5ce4)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff814025e4)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff814185b4)
Location: fs/fat/inode.c:1528
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
