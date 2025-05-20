# Function: <code>notesize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8126731d)
Location: fs/binfmt_elf.c:1330
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269ebc)
Location: fs/binfmt_elf.c:1330
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81286c0a)
Location: fs/proc/kcore.c:277
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812949fe)
Location: fs/binfmt_elf.c:1338
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81297626)
Location: fs/binfmt_elf.c:1338
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812b3ddb)
Location: fs/proc/kcore.c:277
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a96bc)
Location: fs/binfmt_elf.c:1338
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac12f)
Location: fs/binfmt_elf.c:1338
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812c966b)
Location: fs/proc/kcore.c:277
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b4bc0)
Location: fs/binfmt_elf.c:1396
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b7ae0)
Location: fs/binfmt_elf.c:1396
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812d6980)
Location: fs/proc/kcore.c:278
Inline: True
Direct callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
**Symbols:**

```
ffffffff812b4bc0-ffffffff812b4be9: notesize.isra.5 (STB_LOCAL)
ffffffff812b7ae0-ffffffff812b7b09: notesize.isra.5 (STB_LOCAL)
ffffffff812d6980-ffffffff812d69a9: notesize.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d8440)
Location: fs/binfmt_elf.c:1410
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812db320)
Location: fs/binfmt_elf.c:1410
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812fb1d0)
Location: fs/proc/kcore.c:279
Inline: True
Direct callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
**Symbols:**

```
ffffffff812d8440-ffffffff812d8469: notesize.isra.6 (STB_LOCAL)
ffffffff812db320-ffffffff812db349: notesize.isra.6 (STB_LOCAL)
ffffffff812fb1d0-ffffffff812fb1f9: notesize.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303f30)
Location: fs/binfmt_elf.c:1422
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81307840)
Location: fs/binfmt_elf.c:1422
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328790)
Location: fs/proc/kcore.c:288
Inline: True
Direct callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
**Symbols:**

```
ffffffff81303f30-ffffffff81303f59: notesize.isra.7 (STB_LOCAL)
ffffffff81307840-ffffffff81307869: notesize.isra.7 (STB_LOCAL)
ffffffff81328790-ffffffff813287b9: notesize.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81319680)
Location: fs/binfmt_elf.c:1422
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d050)
Location: fs/binfmt_elf.c:1422
Inline: True
```
**Symbols:**

```
ffffffff81319680-ffffffff813196a9: notesize.isra.7 (STB_LOCAL)
ffffffff8131d050-ffffffff8131d079: notesize.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81340fa0)
Location: fs/binfmt_elf.c:1429
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813448b0)
Location: fs/binfmt_elf.c:1429
Inline: True
```
**Symbols:**

```
ffffffff81340fa0-ffffffff81340fc9: notesize.isra.0 (STB_LOCAL)
ffffffff813448b0-ffffffff813448d9: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81359440)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135cbe0)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffffffff81359440-ffffffff81359469: notesize.isra.0 (STB_LOCAL)
ffffffff8135cbe0-ffffffff8135cc09: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139ea70)
Location: fs/binfmt_elf.c:1521
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813a1b80)
Location: fs/binfmt_elf.c:1521
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8139ea70-ffffffff8139eaa0: notesize (STB_LOCAL)
ffffffff813a1b80-ffffffff813a1bb0: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0240)
Location: fs/binfmt_elf.c:1429
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813b2f30)
Location: fs/binfmt_elf.c:1429
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff813b0240-ffffffff813b0270: notesize (STB_LOCAL)
ffffffff813b2f30-ffffffff813b2f60: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b7370)
Location: fs/binfmt_elf.c:1432
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba010)
Location: fs/binfmt_elf.c:1432
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff813b7370-ffffffff813b73a0: notesize (STB_LOCAL)
ffffffff813ba010-ffffffff813ba040: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81407050)
Location: fs/binfmt_elf.c:1432
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff81409d00)
Location: fs/binfmt_elf.c:1432
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff81407050-ffffffff81407080: notesize (STB_LOCAL)
ffffffff81409d00-ffffffff81409d30: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147bba0)
Location: fs/binfmt_elf.c:1467
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147e9b0)
Location: fs/binfmt_elf.c:1467
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8147bba0-ffffffff8147bbd8: notesize (STB_LOCAL)
ffffffff8147e9b0-ffffffff8147e9e8: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150e5d0)
Location: fs/binfmt_elf.c:1462
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff81511610)
Location: fs/binfmt_elf.c:1462
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8150e5d0-ffffffff8150e608: notesize (STB_LOCAL)
ffffffff81511610-ffffffff81511648: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81545d90)
Location: fs/binfmt_elf.c:1467
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff81548ef0)
Location: fs/binfmt_elf.c:1467
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff81545d90-ffffffff81545dc8: notesize (STB_LOCAL)
ffffffff81548ef0-ffffffff81548f28: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157b270)
Location: fs/binfmt_elf.c:1402
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:fill_thread_core_info
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157e210)
Location: fs/binfmt_elf.c:1402
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8157b270-ffffffff8157b2a8: notesize (STB_LOCAL)
ffffffff8157e210-ffffffff8157e248: notesize (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041e070)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010421800)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffff80001041e070-ffff80001041e0bc: notesize.isra.0 (STB_LOCAL)
ffff800010421800-ffff80001042184c: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int notesize(struct memelfnote *en);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e6530)
Location: fs/binfmt_elf.c:1403
Inline: False
```
```
In fs/binfmt_elf_fdpic.c (c05e97b8)
Location: fs/binfmt_elf_fdpic.c:1265
Inline: False
Direct callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
**Symbols:**

```
c05e6530-c05e6570: notesize (STB_LOCAL)
c05e97b8-c05e97f8: notesize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (c00000000052ca70)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000530740)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
c00000000052ca70-c00000000052cad0: notesize.isra.0 (STB_LOCAL)
c000000000530740-c0000000005307a0: notesize.isra.0 (STB_LOCAL)
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
In fs/binfmt_elf.c (ffffffe0002c0f86)
Location: fs/binfmt_elf.c:1403
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81351a20)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813551c0)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffffffff81351a20-ffffffff81351a49: notesize.isra.0 (STB_LOCAL)
ffffffff813551c0-ffffffff813551e9: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81342700)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345e80)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffffffff81342700-ffffffff81342729: notesize.isra.0 (STB_LOCAL)
ffffffff81345e80-ffffffff81345ea9: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8134f4f0)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81352c90)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffffffff8134f4f0-ffffffff8134f519: notesize.isra.0 (STB_LOCAL)
ffffffff81352c90-ffffffff81352cb9: notesize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81362a70)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81366450)
Location: fs/binfmt_elf.c:1403
Inline: True
```
**Symbols:**

```
ffffffff81362a70-ffffffff81362a99: notesize.isra.0 (STB_LOCAL)
ffffffff81366450-ffffffff81366479: notesize.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
