# Function: <code>read_part_sector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff813ce594)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff813ce9c2)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff813cf177)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff813cfb42)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff813d0e91)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
```
```
In block/partitions/msdos.c (ffffffff813d21d2)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
```
```
In block/partitions/osf.c (ffffffff813d31a2)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff813d3342)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff813d3502)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff813d3822)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff813d3a08)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff813d4a62)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff813d4c52)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff81413641)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81413e1e)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8141462e)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814150fc)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814167e7)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814184b5)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81418afb)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81418d0b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81418f2b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814192bb)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8141951c)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8141a5db)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8141a84b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff8142eb71)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8142f34e)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8142fb5e)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8143062c)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81431d17)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814339e5)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff8143402b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8143423b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8143445b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814347eb)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81434a4c)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81435b0b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81435d7b)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff8143beb1)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8143c498)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8143cbee)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8143d606)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8143ecd7)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814407f7)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81440cdb)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81440e97)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814410ab)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814413d7)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814415ef)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814425a7)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814427cb)
Location: block/partitions/check.h:30
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff81467ec6)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81468578)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81468dee)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814698c7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8146b0c7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff8146ce8c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff8146d4ab)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8146d6d7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8146d94b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8146dcc7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8146df2f)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8146ef17)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8146f1ab)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff8149bd21)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c5c9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149cc2e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8149d84e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149eac7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814a0d55)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814a13cb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a1607)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a189b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1c27)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a1e93)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814a3009)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a32ab)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814b6031)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b68e9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b6f4e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814b7b6e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b8e67)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814bb115)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814bb78b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bb9c7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbc5b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bbfe9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bc253)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814bd1e9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd48b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814e4591)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4e87)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e54fe)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e613a)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7b44)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814e9793)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814e9deb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea029)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea2cb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea65b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ea8cb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814eb89b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ebb3b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814fd951)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe3fe)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fe8ce)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814ff50a)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81500f14)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81502b57)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff815031ab)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815033e9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8150368b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503a1b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81503c87)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81504c5b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81504efb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155dd70)
Location: block/partitions/core.c:761
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff8155dd70-ffffffff8155de59: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81579b70)
Location: block/partitions/core.c:685
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81579b70-ffffffff81579c65: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815818a0)
Location: block/partitions/core.c:662
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff815818a0-ffffffff81581998: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e6cb0)
Location: block/partitions/core.c:717
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff815e6cb0-ffffffff815e6d96: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695e30)
Location: block/partitions/core.c:705
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff81695e30-ffffffff81695f9d: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:707
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff82076b27-ffffffff82076b41: read_part_sector.cold (STB_LOCAL)
ffffffff817551e0-ffffffff817552b8: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:707
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff820f6942-ffffffff820f695f: read_part_sector.cold (STB_LOCAL)
ffffffff817914c0-ffffffff8179158d: read_part_sector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *read_part_sector(struct parsed_partitions *state, sector_t n, Sector *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/core.c (0)
Location: block/partitions/core.c:716
Inline: False
Direct callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
**Symbols:**

```
ffffffff821d3d95-ffffffff821d3dad: read_part_sector.cold (STB_LOCAL)
ffffffff817d4dc0-ffffffff817d4e99: read_part_sector (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffff8000105ff4dc)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff8000105fff64)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff80001060046c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff8000106010e4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603094)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
```
In block/partitions/msdos.c (ffff800010604940)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffff8000106050f0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff8000106053b8)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605698)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605a6c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff800010605fc8)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffff800010606bb0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010606e98)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (c07aa794)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07ab298)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07ab758)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c07ac4fc)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae650)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c07afbcc)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c07b02c0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b04d0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b0740)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0acc)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b0dc8)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c07b1ed4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b217c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (c00000000079967c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a5b4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079ac28)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bcb4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c00000000079e890)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c0000000007a06e0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c0000000007a0d80)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a11b0)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1568)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1a50)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1e0c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a3280)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a3690)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffe00043aa40)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffe00043b6e6)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffe00043bbcc)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffe00043c600)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffe00043e6ac)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffe00043f8e4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffe00043fd0a)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffe00043fe94)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffe00044012a)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffe000440490)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffe00044063c)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffe000441aa2)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffe000441c72)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814f5f31)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f69de)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f6eae)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f7aea)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f94f4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814fb137)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814fb78b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fb9c9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbc6b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fbffb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fc267)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814fd23b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd4db)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814e6441)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e6eee)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e73be)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e7ffa)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9a04)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814eb647)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814ebc9b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ebed9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec17b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec50b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ec777)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814ed74b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ed9eb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff814f1fc1)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2a6e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f2f3e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f3b7a)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f5584)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814f71c7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814f781b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7a59)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7cfb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f808b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f82f7)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814f92cb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f956b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/amiga.c (ffffffff8150b021)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150bace)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150bf9e)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8150cbda)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e5e4)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81510227)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff8151087b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510ab9)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510d5b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815110eb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81511357)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8151232b)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815125cb)
Location: block/partitions/check.h:31
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
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
