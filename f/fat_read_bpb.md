# Function: <code>fat_read_bpb</code>

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
In fs/fat/inode.c (ffffffff812fce94)
Location: fs/fat/inode.c:1345
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
In fs/fat/inode.c (ffffffff81330b5f)
Location: fs/fat/inode.c:1435
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
In fs/fat/inode.c (ffffffff813468af)
Location: fs/fat/inode.c:1445
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
In fs/fat/inode.c (ffffffff8135b259)
Location: fs/fat/inode.c:1445
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
In fs/fat/inode.c (ffffffff8137ff5c)
Location: fs/fat/inode.c:1445
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
In fs/fat/inode.c (ffffffff813ae7de)
Location: fs/fat/inode.c:1467
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
In fs/fat/inode.c (ffffffff813c79d8)
Location: fs/fat/inode.c:1459
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
In fs/fat/inode.c (ffffffff813f25a5)
Location: fs/fat/inode.c:1454
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
In fs/fat/inode.c (ffffffff8140c4a8)
Location: fs/fat/inode.c:1456
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
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1456
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814593b0-ffffffff81459526: fat_read_bpb (STB_LOCAL)
ffffffff8145b9bd-ffffffff8145ba87: fat_read_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1455
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81475700-ffffffff81475876: fat_read_bpb (STB_LOCAL)
ffffffff81bed904-ffffffff81bed9ce: fat_read_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1455
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8147b170-ffffffff8147b2e6: fat_read_bpb (STB_LOCAL)
ffffffff81bdfa08-ffffffff81bdfad2: fat_read_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1456
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814d2790-ffffffff814d2906: fat_read_bpb (STB_LOCAL)
ffffffff81ccfef1-ffffffff81ccffbb: fat_read_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1460
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8155f7c0-ffffffff8155f949: fat_read_bpb (STB_LOCAL)
ffffffff81e8314d-ffffffff81e831f9: fat_read_bpb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81601ad0)
Location: fs/fat/inode.c:1455
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81601ad0-ffffffff81601cee: fat_read_bpb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff816399c0)
Location: fs/fat/inode.c:1455
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff816399c0-ffffffff81639be4: fat_read_bpb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_read_bpb(struct super_block *sb, struct fat_boot_sector *b, int silent, struct fat_bios_param_block *bpb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81672eb0)
Location: fs/fat/inode.c:1463
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81672eb0-ffffffff816730d4: fat_read_bpb (STB_LOCAL)
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
In fs/fat/inode.c (ffff8000104ed324)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (c06aaeb8)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (c00000000062bec4)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (ffffffe00035d74e)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (ffffffff81404a88)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (ffffffff813f5508)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (ffffffff81401e08)
Location: fs/fat/inode.c:1456
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
In fs/fat/inode.c (ffffffff81417dd8)
Location: fs/fat/inode.c:1456
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
