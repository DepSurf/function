# Function: <code>ldm_get_vstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff813d00b0)
Location: block/partitions/ldm.c:758
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff813d00b0-ffffffff813d0125: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81415520)
Location: block/partitions/ldm.c:706
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81415520-ffffffff81415595: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81430a50)
Location: block/partitions/ldm.c:706
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81430a50-ffffffff81430ac5: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8143d910)
Location: block/partitions/ldm.c:706
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff8143d910-ffffffff8143d9e8: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81469c60)
Location: block/partitions/ldm.c:706
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81469c60-ffffffff81469d38: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:706
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff8149db60-ffffffff8149dc0f: ldm_get_vstr (STB_LOCAL)
ffffffff8149f694-ffffffff8149f6bc: ldm_get_vstr.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:706
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814b7e80-ffffffff814b7f2f: ldm_get_vstr (STB_LOCAL)
ffffffff814b9a41-ffffffff814b9a69: ldm_get_vstr.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff814e656c)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814e64d0-ffffffff814e657f: ldm_get_vstr (STB_LOCAL)
ffffffff814e8132-ffffffff814e815b: ldm_get_vstr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff814ff93c)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814ff8a0-ffffffff814ff94f: ldm_get_vstr (STB_LOCAL)
ffffffff81501502-ffffffff8150152b: ldm_get_vstr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81560530-ffffffff815605de: ldm_get_vstr.isra.0 (STB_LOCAL)
ffffffff81562198-ffffffff815621be: ldm_get_vstr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff8157c020-ffffffff8157c0ce: ldm_get_vstr.isra.0 (STB_LOCAL)
ffffffff81bf3095-ffffffff81bf30bb: ldm_get_vstr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81583b00-ffffffff81583bae: ldm_get_vstr.isra.0 (STB_LOCAL)
ffffffff81be4f62-ffffffff81be4f88: ldm_get_vstr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff815e92e0-ffffffff815e938e: ldm_get_vstr.isra.0 (STB_LOCAL)
ffffffff81cd92f6-ffffffff81cd931c: ldm_get_vstr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81698c20-ffffffff81698ce3: ldm_get_vstr.isra.0 (STB_LOCAL)
ffffffff81e8cd78-ffffffff81e8cd9e: ldm_get_vstr.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff81757e40)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81757e40-ffffffff81757f29: ldm_get_vstr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff817953c0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff817953c0-ffffffff8179543e: ldm_get_vstr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d8d20)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff817d8d20-ffffffff817d8d9e: ldm_get_vstr.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffff800010601680)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffff800010601680-ffff800010601718: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c07ac8b0)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
c07ac8b0-c07ac940: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c00000000079c4e0)
Location: block/partitions/ldm.c:692
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
c00000000079c4e0-c00000000079c5b4: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffe00043ca18)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffe00043ca18-ffffffe00043ca9a: ldm_get_vstr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff814f7f1c)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814f7e80-ffffffff814f7f2f: ldm_get_vstr (STB_LOCAL)
ffffffff814f9ae2-ffffffff814f9b0b: ldm_get_vstr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff814e842c)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814e8390-ffffffff814e843f: ldm_get_vstr (STB_LOCAL)
ffffffff814e9ff2-ffffffff814ea01b: ldm_get_vstr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff814f3fac)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814f3f10-ffffffff814f3fbf: ldm_get_vstr (STB_LOCAL)
ffffffff814f5b72-ffffffff814f5b9b: ldm_get_vstr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ldm_get_vstr(const u8 *block, u8 *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (ffffffff8150d00c)
Location: block/partitions/ldm.c:692
Inline: True
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff8150cf70-ffffffff8150d01f: ldm_get_vstr (STB_LOCAL)
ffffffff8150ebd2-ffffffff8150ebfb: ldm_get_vstr.cold (STB_LOCAL)
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
