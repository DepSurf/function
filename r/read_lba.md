# Function: <code>read_lba</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff813cf100)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff813d3950)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff813cf100-ffffffff813cf29a: read_lba (STB_LOCAL)
ffffffff813d3950-ffffffff813d3b52: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814143f0)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81419450)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff814143f0-ffffffff814145f3: read_lba (STB_LOCAL)
ffffffff81419450-ffffffff814196b9: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8142f920)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81434980)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff8142f920-ffffffff8142fb23: read_lba (STB_LOCAL)
ffffffff81434980-ffffffff81434be9: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8143ca70)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81441540)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8143ca70-ffffffff8143cbbf: read_lba (STB_LOCAL)
ffffffff81441540-ffffffff81441725: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff81468c40)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff8146de80)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81468c40-ffffffff81468dbd: read_lba (STB_LOCAL)
ffffffff8146de80-ffffffff8146e09a: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8149ca50)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814a1de0)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:find_valid_gpt
```
**Symbols:**

```
ffffffff8149ca50-ffffffff8149cbf7: read_lba (STB_LOCAL)
ffffffff814a1de0-ffffffff814a2000: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814b6d70)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814bc1a0)
Location: block/partitions/efi.c:251
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814b6d70-ffffffff814b6f17: read_lba (STB_LOCAL)
ffffffff814bc1a0-ffffffff814bc3c0: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814e52f0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814ea820)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814e52f0-ffffffff814e54d0: read_lba (STB_LOCAL)
ffffffff814ea820-ffffffff814eaa3f: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814fe6c0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81503be0)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814fe6c0-ffffffff814fe8a0: read_lba (STB_LOCAL)
ffffffff81503be0-ffffffff81503df9: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8155ee30)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81564600)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:alloc_read_gpt_header
```
**Symbols:**

```
ffffffff8155ee30-ffffffff8155efcf: read_lba (STB_LOCAL)
ffffffff81564600-ffffffff81564835: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8157a9f0)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff8157f720)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:alloc_read_gpt_header
```
**Symbols:**

```
ffffffff8157a9f0-ffffffff8157ab8c: read_lba (STB_LOCAL)
ffffffff8157f720-ffffffff8157f94f: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff81582720)
Location: block/partitions/aix.c:95
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff81587260)
Location: block/partitions/efi.c:237
Inline: False
```
**Symbols:**

```
ffffffff81582720-ffffffff815828bc: read_lba (STB_LOCAL)
ffffffff81587260-ffffffff81587490: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/aix.c (ffffffff815e7e3b)
Location: block/partitions/aix.c:79
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff815ecde0)
Location: block/partitions/efi.c:235
Inline: False
```
**Symbols:**

```
ffffffff815e7a80-ffffffff815e7bd0: read_lba.part.0 (STB_LOCAL)
ffffffff815ecde0-ffffffff815ecfeb: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff81696fa0)
Location: block/partitions/aix.c:79
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff8169d320)
Location: block/partitions/efi.c:235
Inline: False
Direct callers:
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff81696fa0-ffffffff8169714e: read_lba (STB_LOCAL)
ffffffff8169d320-ffffffff8169d56a: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff81755f00)
Location: block/partitions/aix.c:79
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff8175be00)
Location: block/partitions/efi.c:235
Inline: False
Direct callers:
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff81755f00-ffffffff81756036: read_lba (STB_LOCAL)
ffffffff8175be00-ffffffff8175bf9d: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff81792c10)
Location: block/partitions/aix.c:79
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff8179a670)
Location: block/partitions/efi.c:235
Inline: False
Direct callers:
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff81792c10-ffffffff81792d46: read_lba (STB_LOCAL)
ffffffff8179a670-ffffffff8179a80d: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff817d6520)
Location: block/partitions/aix.c:79
Inline: False
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff817de0a0)
Location: block/partitions/efi.c:235
Inline: False
Direct callers:
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:is_gpt_valid
```
**Symbols:**

```
ffffffff817d6520-ffffffff817d6656: read_lba (STB_LOCAL)
ffffffff817de0a0-ffffffff817de23d: read_lba (STB_LOCAL)
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
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffff8000106002c0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffff800010605f18)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffff8000106002c0-ffff800010600434: read_lba (STB_LOCAL)
ffff800010605f18-ffff8000106060c0: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (c07ab590)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (c07b0d30)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
c07ab590-c07ab724: read_lba (STB_LOCAL)
c07b0d30-c07b0ed0: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (c00000000079a9b0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (c0000000007a1d50)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:find_valid_gpt
```
**Symbols:**

```
c00000000079a9b0-c00000000079abd8: read_lba (STB_LOCAL)
c0000000007a1d50-c0000000007a1fd4: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffe00043baa6)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffe0004405d6)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffe0004405d6-ffffffe0004406fc: read_lba (STB_LOCAL)
ffffffe00043baa6-ffffffe00043bb9e: read_lba (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814f6ca0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814fc1c0)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814f6ca0-ffffffff814f6e80: read_lba (STB_LOCAL)
ffffffff814fc1c0-ffffffff814fc3d9: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814e71b0)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814ec6d0)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814e71b0-ffffffff814e7390: read_lba (STB_LOCAL)
ffffffff814ec6d0-ffffffff814ec8e9: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff814f2d30)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff814f8250)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814f2d30-ffffffff814f2f10: read_lba (STB_LOCAL)
ffffffff814f8250-ffffffff814f8469: read_lba (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
size_t read_lba(struct parsed_partitions *state, u64 lba, u8 *buffer, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partitions/aix.c (ffffffff8150bd90)
Location: block/partitions/aix.c:96
Inline: True
Direct callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/efi.c (ffffffff815112b0)
Location: block/partitions/efi.c:237
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8150bd90-ffffffff8150bf70: read_lba (STB_LOCAL)
ffffffff815112b0-ffffffff815114c9: read_lba (STB_LOCAL)
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
