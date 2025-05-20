# Function: <code>put_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff813ce4b0)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff813ceb74)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff813cf411)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff813cf8a0)
Location: block/partitions/check.h:41
Inline: False
```
```
In block/partitions/mac.c (ffffffff813cfc50)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff813d1f3f)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff813d2120)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
Direct callers:
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_minix
```
```
In block/partitions/osf.c (ffffffff813d3235)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff813d33d3)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff813d35ed)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff813d389e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff813d4616)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff813d4abb)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff813d4b90)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff813ce4b0-ffffffff813ce531: put_partition (STB_LOCAL)
ffffffff813cf8a0-ffffffff813cf921: put_partition (STB_LOCAL)
ffffffff813d2120-ffffffff813d219c: put_partition.part.4 (STB_LOCAL)
ffffffff813d4b90-ffffffff813d4c11: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff81413560)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81413cc2)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8141473e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff81414cc0)
Location: block/partitions/check.h:41
Inline: False
```
```
In block/partitions/mac.c (ffffffff814150c2)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8141747e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff81418427)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff81418b95)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81418d9e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81419009)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8141937a)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8141a119)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8141a63f)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8141a790)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81413560-ffffffff814135e1: put_partition (STB_LOCAL)
ffffffff81414cc0-ffffffff81414d41: put_partition (STB_LOCAL)
ffffffff81417710-ffffffff8141778c: put_partition.part.4 (STB_LOCAL)
ffffffff8141a790-ffffffff8141a811: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff8142ea90)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8142f1f2)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8142fc6e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814301f0)
Location: block/partitions/check.h:41
Inline: False
```
```
In block/partitions/mac.c (ffffffff814305f2)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814329ae)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff81433957)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814340c5)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814342ce)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81434539)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814348aa)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81435649)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff81435b6f)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81435cc0)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8142ea90-ffffffff8142eb11: put_partition (STB_LOCAL)
ffffffff814301f0-ffffffff81430271: put_partition (STB_LOCAL)
ffffffff81432c40-ffffffff81432cbc: put_partition.part.4 (STB_LOCAL)
ffffffff81435cc0-ffffffff81435d41: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff8143bdc0)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8143c410)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8143cd83)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff8143d230)
Location: block/partitions/check.h:41
Inline: False
```
```
In block/partitions/mac.c (ffffffff8143d644)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8143f79e)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff81440597)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff81440d80)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81440f28)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814411a1)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8144147d)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8144216f)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff81442692)
Location: block/partitions/check.h:41
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81442710)
Location: block/partitions/check.h:41
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8143bdc0-ffffffff8143be41: put_partition (STB_LOCAL)
ffffffff8143d230-ffffffff8143d2b1: put_partition (STB_LOCAL)
ffffffff8143fb70-ffffffff8143fbec: put_partition.part.3 (STB_LOCAL)
ffffffff81442710-ffffffff81442791: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff81467dd0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814684f0)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81468f50)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814694c0)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff81469905)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8146bc30)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff8146cbfe)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8146d550)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8146d768)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8146da41)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8146dd97)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8146eadf)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8146f03a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8146f0f0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81467dd0-ffffffff81467e51: put_partition (STB_LOCAL)
ffffffff814694c0-ffffffff81469541: put_partition (STB_LOCAL)
ffffffff8146c030-ffffffff8146c0ac: put_partition.part.4 (STB_LOCAL)
ffffffff8146f0f0-ffffffff8146f171: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff8149bc60)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c455)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149d13b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff8149d300)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff8149d89f)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149f43d)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814a0fdd)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814a1487)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a1697)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a1977)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1d0d)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a2bb9)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814a30d4)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a31f0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8149bc60-ffffffff8149bce3: put_partition (STB_LOCAL)
ffffffff8149d300-ffffffff8149d383: put_partition (STB_LOCAL)
ffffffff8149fee0-ffffffff8149ff5c: put_partition.part.5 (STB_LOCAL)
ffffffff814a31f0-ffffffff814a3273: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814b5f70)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b6775)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b745b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814b7620)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814b7bbf)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b97ea)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814bb39d)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814bb847)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bba57)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbd3b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bc0d2)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bce28)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814bd2b4)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd3d0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814b5f70-ffffffff814b5ff3: put_partition (STB_LOCAL)
ffffffff814b7620-ffffffff814b76a3: put_partition (STB_LOCAL)
ffffffff814ba2a0-ffffffff814ba31c: put_partition.part.5 (STB_LOCAL)
ffffffff814bd3d0-ffffffff814bd453: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814e44d0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4cdd)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e5a55)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814e5c00)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814e6193)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7eb2)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814e9a1a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814e9e8b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea0b6)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea3a6)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea748)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814eb4f8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814eb96a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814eba80)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814e44d0-ffffffff814e4553: put_partition (STB_LOCAL)
ffffffff814e5c00-ffffffff814e5c83: put_partition (STB_LOCAL)
ffffffff814e8930-ffffffff814e89ac: put_partition.part.0 (STB_LOCAL)
ffffffff814eba80-ffffffff814ebb03: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814fd890)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe017)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fee25)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814fefd0)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814ff563)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81501282)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff81502dde)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8150324b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81503476)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81503766)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503b08)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815048be)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff81504d2a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81504e40)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814fd890-ffffffff814fd913: put_partition (STB_LOCAL)
ffffffff814fefd0-ffffffff814ff053: put_partition (STB_LOCAL)
ffffffff81501d00-ffffffff81501d7c: put_partition.part.0 (STB_LOCAL)
ffffffff81504e40-ffffffff81504ec3: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff8155e010)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8155e740)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8155f4de)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff8155f690)
Location: block/partitions/check.h:38
Inline: False
```
```
In block/partitions/mac.c (ffffffff8155fc1d)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8156111b)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff815636f0)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff81563b19)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81563d6c)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81564041)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815643b3)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81565238)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8156567f)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81565750)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8155e010-ffffffff8155e092: put_partition (STB_LOCAL)
ffffffff8155f690-ffffffff8155f712: put_partition (STB_LOCAL)
ffffffff81562650-ffffffff815626cb: put_partition.part.0 (STB_LOCAL)
ffffffff81565750-ffffffff815657d2: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff81579c70)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8157a389)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8157b087)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff8157b200)
Location: block/partitions/check.h:38
Inline: False
```
```
In block/partitions/mac.c (ffffffff8157b73d)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8157cc0b)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff8157e820)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8157ec49)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8157ee9c)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8157f163)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8157f4f0)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81580332)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8158061c)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815806e0)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81579c70-ffffffff81579cf2: put_partition (STB_LOCAL)
ffffffff8157b200-ffffffff8157b282: put_partition (STB_LOCAL)
ffffffff8157d7e0-ffffffff8157d85b: put_partition.part.0 (STB_LOCAL)
ffffffff815806e0-ffffffff81580762: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff815819a0)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815820b9)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81582db7)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff81582f30)
Location: block/partitions/check.h:38
Inline: False
```
```
In block/partitions/mac.c (ffffffff81583444)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81584669)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff815863cb)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff815867a9)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815869fb)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81586cc9)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81587030)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81587eaa)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8158818c)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81588250)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff815819a0-ffffffff81581a22: put_partition (STB_LOCAL)
ffffffff81582f30-ffffffff81582fb2: put_partition (STB_LOCAL)
ffffffff81585370-ffffffff815853eb: put_partition.part.0 (STB_LOCAL)
ffffffff81588250-ffffffff815882d2: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff815e6da0)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815e7416)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e8151)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff815e82c0)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/mac.c (ffffffff815e8d34)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff815e9e49)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff815ebdfe)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff815ec2f9)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815ec53e)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815ec7e5)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815ecbad)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815edb49)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff815ede29)
Location: block/partitions/check.h:38
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815edef0)
Location: block/partitions/check.h:38
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff815e6da0-ffffffff815e6e22: put_partition (STB_LOCAL)
ffffffff815e82c0-ffffffff815e8342: put_partition (STB_LOCAL)
ffffffff815eada0-ffffffff815eae1b: put_partition.part.0 (STB_LOCAL)
ffffffff815edef0-ffffffff815edf72: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff81695fa0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff816967e5)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81697787)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff81697920)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/mac.c (ffffffff816984cb)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81699799)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff8169be8d)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8169c4fd)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c858)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cc5d)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169d079)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169e0e6)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8169e403)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e5a0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81695fa0-ffffffff8169606a: put_partition (STB_LOCAL)
ffffffff81697920-ffffffff816979ea: put_partition (STB_LOCAL)
ffffffff8169a920-ffffffff8169a9dc: put_partition.part.0 (STB_LOCAL)
ffffffff8169e5a0-ffffffff8169e66a: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff817552d0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff817559cd)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff817565bd)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff81756750)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
```
In block/partitions/mac.c (ffffffff81757396)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81758ba9)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff8175aeb8)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8175b30d)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8175b4d4)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8175b707)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8175ba2c)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8175cb0e)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8175ce35)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8175cf00)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff817552d0-ffffffff8175539a: put_partition (STB_LOCAL)
ffffffff81756750-ffffffff8175681a: put_partition (STB_LOCAL)
ffffffff81759de0-ffffffff81759e9c: put_partition.part.0 (STB_LOCAL)
ffffffff8175cf00-ffffffff8175cfca: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff817915a0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8179245f)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81792a40)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff81793630)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/cmdline.c:add_part
```
```
In block/partitions/mac.c (ffffffff81794380)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81794f50)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff81798d15)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff817991b0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81799520)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff817998c0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81799de0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8179a4a0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff8179b5b0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8179b900)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff817915a0-ffffffff81791760: put_partition (STB_LOCAL)
ffffffff817920e0-ffffffff81792291: put_partition.part.0 (STB_LOCAL)
ffffffff81792a40-ffffffff81792c00: put_partition (STB_LOCAL)
ffffffff81793630-ffffffff817937f0: put_partition (STB_LOCAL)
ffffffff81794380-ffffffff81794540: put_partition (STB_LOCAL)
ffffffff81794f50-ffffffff81795110: put_partition (STB_LOCAL)
ffffffff817972d0-ffffffff81797481: put_partition.part.0 (STB_LOCAL)
ffffffff817991b0-ffffffff81799370: put_partition (STB_LOCAL)
ffffffff81799520-ffffffff817996e0: put_partition (STB_LOCAL)
ffffffff817998c0-ffffffff81799a80: put_partition (STB_LOCAL)
ffffffff81799de0-ffffffff81799fa0: put_partition (STB_LOCAL)
ffffffff8179a4a0-ffffffff8179a660: put_partition (STB_LOCAL)
ffffffff8179b5b0-ffffffff8179b770: put_partition (STB_LOCAL)
ffffffff8179b900-ffffffff8179bac0: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff817d4eb0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff817d5d6f)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff817d6350)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff817d6f40)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/cmdline.c:add_part
```
```
In block/partitions/mac.c (ffffffff817d7ce0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff817d88b0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_create_data_partitions
```
```
In block/partitions/msdos.c (ffffffff817dc745)
Location: block/partitions/check.h:37
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff817dcbe0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff817dcf50)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff817dd2f0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff817dd810)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff817dded0)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff817df010)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff817df360)
Location: block/partitions/check.h:37
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff817d4eb0-ffffffff817d5070: put_partition (STB_LOCAL)
ffffffff817d59f0-ffffffff817d5ba1: put_partition.part.0 (STB_LOCAL)
ffffffff817d6350-ffffffff817d6510: put_partition (STB_LOCAL)
ffffffff817d6f40-ffffffff817d7100: put_partition (STB_LOCAL)
ffffffff817d7ce0-ffffffff817d7ea0: put_partition (STB_LOCAL)
ffffffff817d88b0-ffffffff817d8a70: put_partition (STB_LOCAL)
ffffffff817dad00-ffffffff817daeb1: put_partition.part.0 (STB_LOCAL)
ffffffff817dcbe0-ffffffff817dcda0: put_partition (STB_LOCAL)
ffffffff817dcf50-ffffffff817dd110: put_partition (STB_LOCAL)
ffffffff817dd2f0-ffffffff817dd4b0: put_partition (STB_LOCAL)
ffffffff817dd810-ffffffff817dd9d0: put_partition (STB_LOCAL)
ffffffff817dded0-ffffffff817de090: put_partition (STB_LOCAL)
ffffffff817df010-ffffffff817df1d0: put_partition (STB_LOCAL)
ffffffff817df360-ffffffff817df520: put_partition (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffff8000105ff3e8)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff8000105ffb9c)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff800010600990)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffff800010600b78)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffff800010601140)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603610)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffff8000106048e0)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffff800010605190)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff800010605458)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605794)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605b64)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff8000106068f8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffff800010606cbc)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010606dc8)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffff8000105ff3e8-ffff8000105ff484: put_partition (STB_LOCAL)
ffff800010600b78-ffff800010600c14: put_partition (STB_LOCAL)
ffff800010603b00-ffff800010603b88: put_partition.part.0 (STB_LOCAL)
ffff800010606dc8-ffff800010606e64: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (c07aa694)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07aaeec)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07abc54)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (c07abda8)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (c07ac544)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae9e4)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (c07b0194)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (c07b0374)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b0584)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b0850)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0bc8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b1bb8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (c07b1fec)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b2098)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
c07aa694-c07aa744: put_partition (STB_LOCAL)
c07abda8-c07abe58: put_partition (STB_LOCAL)
c07aece4-c07aed78: put_partition.part.0 (STB_LOCAL)
c07b2098-c07b2148: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (c000000000799540)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a5e8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079b3a0)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (c00000000079b560)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (c00000000079bd00)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c00000000079ed2c)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (c0000000007a09cc)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (c0000000007a0e5c)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a1284)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1698)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1be0)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a2fa8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (c0000000007a33dc)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a3590)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
c000000000799540-c000000000799608: put_partition (STB_LOCAL)
c00000000079b560-c00000000079b628: put_partition (STB_LOCAL)
c00000000079f100-c00000000079f1ac: put_partition.part.0 (STB_LOCAL)
c0000000007a3590-c0000000007a3658: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffe00043a99e)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffe00043b18a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffe00043bec4)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffe00043c1a4)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffe00043c5ce)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffe00043e994)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffe00043f896)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffe00043fd5a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffe00043ff38)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffe000440214)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffe00044050e)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffe00044166a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffe000441ae4)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffe000441bf0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffe00043c1a4-ffffffe00043c200: put_partition (STB_LOCAL)
ffffffe00043a99e-ffffffe00043a9fa: put_partition (STB_LOCAL)
ffffffe00043ec8c-ffffffe00043ecde: put_partition.part.0 (STB_LOCAL)
ffffffe000441bf0-ffffffe000441c4c: put_partition (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814f5e70)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f65f7)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f7405)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814f75b0)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814f7b43)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f9862)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814fb3be)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814fb82b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fba56)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbd46)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fc0e8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fce9e)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814fd30a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd420)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814f5e70-ffffffff814f5ef3: put_partition (STB_LOCAL)
ffffffff814f75b0-ffffffff814f7633: put_partition (STB_LOCAL)
ffffffff814fa2e0-ffffffff814fa35c: put_partition.part.0 (STB_LOCAL)
ffffffff814fd420-ffffffff814fd4a3: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814e6380)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e6b07)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e7915)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814e7ac0)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814e8053)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9d72)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814eb8ce)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814ebd3b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ebf66)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec256)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec5f8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ed3ae)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814ed81a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ed930)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814e6380-ffffffff814e6403: put_partition (STB_LOCAL)
ffffffff814e7ac0-ffffffff814e7b43: put_partition (STB_LOCAL)
ffffffff814ea7f0-ffffffff814ea86c: put_partition.part.0 (STB_LOCAL)
ffffffff814ed930-ffffffff814ed9b3: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff814f1f00)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2687)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f3495)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff814f3640)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff814f3bd3)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f58f2)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff814f744e)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff814f78bb)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7ae6)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7dd6)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f8178)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f8f2e)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff814f939a)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f94b0)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff814f1f00-ffffffff814f1f83: put_partition (STB_LOCAL)
ffffffff814f3640-ffffffff814f36c3: put_partition (STB_LOCAL)
ffffffff814f6370-ffffffff814f63ec: put_partition.part.0 (STB_LOCAL)
ffffffff814f94b0-ffffffff814f9533: put_partition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void put_partition(struct parsed_partitions *p, int n, sector_t from, sector_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/amiga.c (ffffffff8150af60)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150b6e7)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150c4f5)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/cmdline.c (ffffffff8150c6a0)
Location: block/partitions/check.h:42
Inline: False
```
```
In block/partitions/mac.c (ffffffff8150cc33)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e952)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff815104ae)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
Direct callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
```
```
In block/partitions/osf.c (ffffffff8151091b)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510b46)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510e36)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815111d8)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81511f8e)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/partitions/karma.c (ffffffff815123fa)
Location: block/partitions/check.h:42
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81512510)
Location: block/partitions/check.h:42
Inline: False
Direct callers:
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8150af60-ffffffff8150afe3: put_partition (STB_LOCAL)
ffffffff8150c6a0-ffffffff8150c723: put_partition (STB_LOCAL)
ffffffff8150f3d0-ffffffff8150f44c: put_partition.part.0 (STB_LOCAL)
ffffffff81512510-ffffffff81512593: put_partition (STB_LOCAL)
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
