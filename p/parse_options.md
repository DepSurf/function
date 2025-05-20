# Function: <code>parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b9ea0)
Location: fs/ext4/super.c:1720
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff812fc380)
Location: fs/fat/inode.c:1022
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8131fa70)
Location: fs/pstore/inode.c:248
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff81fa6e00)
Location: drivers/tty/serial/earlycon.c:64
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff812b9ea0-ffffffff812ba109: parse_options (STB_LOCAL)
ffffffff812fc380-ffffffff812fc8f5: parse_options (STB_LOCAL)
ffffffff8131fa70-ffffffff8131fb00: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e8d90)
Location: fs/ext4/super.c:1837
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8132ffa0)
Location: fs/fat/inode.c:1105
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81354f20)
Location: fs/pstore/inode.c:247
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff81fd31e0)
Location: drivers/tty/serial/earlycon.c:91
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff812e8d90-ffffffff812e9028: parse_options (STB_LOCAL)
ffffffff8132ffa0-ffffffff813305aa: parse_options (STB_LOCAL)
ffffffff81354f20-ffffffff81354fc6: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812feb30)
Location: fs/ext4/super.c:1864
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81345d00)
Location: fs/fat/inode.c:1105
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8136b1d0)
Location: fs/pstore/inode.c:252
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff82010ba0)
Location: drivers/tty/serial/earlycon.c:91
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff812feb30-ffffffff812fed69: parse_options (STB_LOCAL)
ffffffff81345d00-ffffffff8134630a: parse_options (STB_LOCAL)
ffffffff8136b1d0-ffffffff8136b276: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813338c0)
Location: fs/ext4/super.c:1922
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8135a790)
Location: fs/fat/inode.c:1105
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8137f8b0)
Location: fs/pstore/inode.c:261
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff820f269d)
Location: drivers/tty/serial/earlycon.c:91
Inline: True
```
**Symbols:**

```
ffffffff813338c0-ffffffff81333b1d: parse_options (STB_LOCAL)
ffffffff8135a790-ffffffff8135ad32: parse_options (STB_LOCAL)
ffffffff8137f8b0-ffffffff8137f955: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81357dd0)
Location: fs/ext4/super.c:1925
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8137f4a0)
Location: fs/fat/inode.c:1105
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff813a49d0)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff826fbe96)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
```
**Symbols:**

```
ffffffff81357dd0-ffffffff8135802d: parse_options (STB_LOCAL)
ffffffff8137f4a0-ffffffff8137fa35: parse_options (STB_LOCAL)
ffffffff813a49d0-ffffffff813a4a75: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81385f90)
Location: fs/ext4/super.c:1963
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1128
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff813d3d70)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff82726199)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff81385f90-ffffffff813861fd: parse_options (STB_LOCAL)
ffffffff813ad9b0-ffffffff813adf0e: parse_options (STB_LOCAL)
ffffffff813afd36-ffffffff813afd98: parse_options.cold.28 (STB_LOCAL)
ffffffff813d3d70-ffffffff813d3e16: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8139eac0)
Location: fs/ext4/super.c:2019
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1120
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff813ee2e0)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff828de36f)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff8139eac0-ffffffff8139ecf6: parse_options (STB_LOCAL)
ffffffff813c6d60-ffffffff813c7432: parse_options (STB_LOCAL)
ffffffff813c91a6-ffffffff813c9208: parse_options.cold.32 (STB_LOCAL)
ffffffff813ee2e0-ffffffff813ee386: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8d30)
Location: fs/ext4/super.c:2063
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1115
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8141a580)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff828f8d85)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813c8d30-ffffffff813c8f51: parse_options (STB_LOCAL)
ffffffff813f1840-ffffffff813f1f12: parse_options (STB_LOCAL)
ffffffff813f3d1d-ffffffff813f3d7f: parse_options.cold (STB_LOCAL)
ffffffff8141a580-ffffffff8141a610: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813e20e0)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff814343f0)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff82901c86)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813e20e0-ffffffff813e2301: parse_options (STB_LOCAL)
ffffffff8140b740-ffffffff8140be12: parse_options (STB_LOCAL)
ffffffff8140dbfd-ffffffff8140dc5f: parse_options.cold (STB_LOCAL)
ffffffff814343f0-ffffffff81434480: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8142f470)
Location: fs/ext4/super.c:2210
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81484040)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff82d18cc4)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff8142f470-ffffffff8142f67a: parse_options (STB_LOCAL)
ffffffff814596b0-ffffffff81459d57: parse_options (STB_LOCAL)
ffffffff8145bb04-ffffffff8145bb63: parse_options.cold (STB_LOCAL)
ffffffff81484040-ffffffff814840c7: parse_options (STB_LOCAL)
ffffffff82d18cc4-ffffffff82d18df7: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81448190)
Location: fs/ext4/super.c:2413
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1126
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff814a1690)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff8300693d)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff81448190-ffffffff8144839a: parse_options (STB_LOCAL)
ffffffff81475a00-ffffffff814760a7: parse_options (STB_LOCAL)
ffffffff81beda4b-ffffffff81bedaaa: parse_options.cold (STB_LOCAL)
ffffffff814a1690-ffffffff814a1717: parse_options (STB_LOCAL)
ffffffff8300693d-ffffffff83006a70: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, struct ext4_parsed_options *ret_opts, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8144d9f0)
Location: fs/ext4/super.c:2440
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1126
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff814a77c0)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff83211526)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff8144d9f0-ffffffff8144dbe7: parse_options (STB_LOCAL)
ffffffff8147b460-ffffffff8147bb19: parse_options (STB_LOCAL)
ffffffff81bdfb4f-ffffffff81bdfbb1: parse_options.cold (STB_LOCAL)
ffffffff814a77c0-ffffffff814a7850: parse_options (STB_LOCAL)
ffffffff83211526-ffffffff8321165b: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, struct ext4_parsed_options *ret_opts, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff814ffab0)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff832fa5e9)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff814a1a80-ffffffff814a1c74: parse_options (STB_LOCAL)
ffffffff81ccdb73-ffffffff81ccdb93: parse_options.cold (STB_LOCAL)
ffffffff814d2af0-ffffffff814d31a9: parse_options (STB_LOCAL)
ffffffff81cd0044-ffffffff81cd00a6: parse_options.cold (STB_LOCAL)
ffffffff814ffab0-ffffffff814ffb40: parse_options (STB_LOCAL)
ffffffff832fa5e9-ffffffff832fa71e: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(struct fs_context *fc, char *options);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81528cd0)
Location: fs/ext4/super.c:2393
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1131
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81590bd0)
Location: fs/pstore/inode.c:239
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff834b2ebf)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff81528cd0-ffffffff81528e9c: parse_options (STB_LOCAL)
ffffffff8155fb30-ffffffff815601ae: parse_options (STB_LOCAL)
ffffffff81e83278-ffffffff81e832d5: parse_options.cold (STB_LOCAL)
ffffffff81590bd0-ffffffff81590c8a: parse_options (STB_LOCAL)
ffffffff834b2ebf-ffffffff834b3021: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(struct fs_context *fc, char *options);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff815c6d90)
Location: fs/ext4/super.c:2370
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81601f60)
Location: fs/fat/inode.c:1126
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81638110)
Location: fs/pstore/inode.c:240
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff83eed860)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
**Symbols:**

```
ffffffff815c6d90-ffffffff815c6f5c: parse_options (STB_LOCAL)
ffffffff81601f60-ffffffff81602624: parse_options (STB_LOCAL)
ffffffff81638110-ffffffff816381ca: parse_options (STB_LOCAL)
ffffffff83eed860-ffffffff83eed9f6: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(struct fs_context *fc, char *options);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff815feb10)
Location: fs/ext4/super.c:2437
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81639e60)
Location: fs/fat/inode.c:1126
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81670510)
Location: fs/pstore/inode.c:240
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff83713520)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
**Symbols:**

```
ffffffff815feb10-ffffffff815fecdc: parse_options (STB_LOCAL)
ffffffff81639e60-ffffffff8163a547: parse_options (STB_LOCAL)
ffffffff81670510-ffffffff816705ca: parse_options (STB_LOCAL)
ffffffff83713520-ffffffff837136e5: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(struct fs_context *fc, char *options);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff816374f0)
Location: fs/ext4/super.c:2454
Inline: False
Direct callers:
  - fs/ext4/super.c:parse_apply_sb_mount_options
```
```
In fs/fat/inode.c (ffffffff81673350)
Location: fs/fat/inode.c:1134
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff816ac440)
Location: fs/pstore/inode.c:237
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff83946f80)
Location: drivers/tty/serial/earlycon.c:93
Inline: True
Direct callers:
  - drivers/tty/serial/earlycon.c:register_earlycon
```
**Symbols:**

```
ffffffff816374f0-ffffffff816376bc: parse_options (STB_LOCAL)
ffffffff81673350-ffffffff81673a37: parse_options (STB_LOCAL)
ffffffff816ac440-ffffffff816ac4fa: parse_options (STB_LOCAL)
ffffffff83946f80-ffffffff83947145: parse_options.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bb4b0)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffff8000104ec140)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffff800010519f90)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffff800011493f08)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffff8000104bb4b0-ffff8000104bb6d0: parse_options (STB_LOCAL)
ffff8000104ec140-ffff8000104ec728: parse_options (STB_LOCAL)
ffff800010519f90-ffff80001051a05c: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067ec40)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (c06aa4d0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (c06d45f8)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (c15947c8)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
c067ec40-c067ee48: parse_options (STB_LOCAL)
c06aa4d0-c06aab78: parse_options (STB_LOCAL)
c06d45f8-c06d46b8: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f1270)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (c00000000062ae60)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (c000000000663910)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (c0000000013a72d8)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
c0000000005f1270-c0000000005f1550: parse_options (STB_LOCAL)
c00000000062ae60-c00000000062b840: parse_options (STB_LOCAL)
c000000000663910-c000000000663a20: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000337880)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffe00035ca0a)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffe0003832a0)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffe00002ec56)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffe000337880-ffffffe000337a3c: parse_options (STB_LOCAL)
ffffffe00035ca0a-ffffffe00035cf6e: parse_options (STB_LOCAL)
ffffffe0003832a0-ffffffe00038333a: parse_options (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813da6c0)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8142c9d0)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff828e946d)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813da6c0-ffffffff813da8e1: parse_options (STB_LOCAL)
ffffffff81403d20-ffffffff814043f2: parse_options (STB_LOCAL)
ffffffff814061dd-ffffffff8140623f: parse_options.cold (STB_LOCAL)
ffffffff8142c9d0-ffffffff8142ca60: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb140)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8141d450)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff828e0920)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813cb140-ffffffff813cb361: parse_options (STB_LOCAL)
ffffffff813f47a0-ffffffff813f4e72: parse_options (STB_LOCAL)
ffffffff813f6c5d-ffffffff813f6cbf: parse_options.cold (STB_LOCAL)
ffffffff8141d450-ffffffff8141d4e0: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7b40)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff81428b70)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff828fcfa9)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813d7b40-ffffffff813d7d61: parse_options (STB_LOCAL)
ffffffff814010a0-ffffffff81401772: parse_options (STB_LOCAL)
ffffffff8140355d-ffffffff814035bf: parse_options.cold (STB_LOCAL)
ffffffff81428b70-ffffffff81428c00: parse_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int parse_options(char *options, struct super_block *sb, long unsigned int *journal_devnum, unsigned int *journal_ioprio, int is_remount);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813ece00)
Location: fs/ext4/super.c:2066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1127
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/inode.c (ffffffff8143fa30)
Location: fs/pstore/inode.c:227
Inline: False
Direct callers:
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_remount
```
```
In drivers/tty/serial/earlycon.c (ffffffff82902ce8)
Location: drivers/tty/serial/earlycon.c:88
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
**Symbols:**

```
ffffffff813ece00-ffffffff813ed021: parse_options (STB_LOCAL)
ffffffff814171d0-ffffffff814178a2: parse_options (STB_LOCAL)
ffffffff8141920d-ffffffff8141926f: parse_options.cold (STB_LOCAL)
ffffffff8143fa30-ffffffff8143fac0: parse_options (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_parsed_options *ret_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *journal_devnum</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *journal_ioprio</code>
</li>
<li>
<b>Param reordered. </b>
<code>options, sb, journal_devnum, journal_ioprio, is_remount</code> ➡️ <code>options, sb, ret_opts, is_remount</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fs_context *fc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ext4_parsed_options *ret_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>int is_remount</code>
</li>
<li>
<b>Param reordered. </b>
<code>options, sb, ret_opts, is_remount</code> ➡️ <code>fc, options</code>
</li>
</ul>
</details>
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
