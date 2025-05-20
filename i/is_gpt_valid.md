# Function: <code>is_gpt_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff813d3b60)
Location: block/partitions/efi.c:351
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff813d3b60-ffffffff813d3fd4: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff814196c0)
Location: block/partitions/efi.c:351
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814196c0-ffffffff81419ae9: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff81434bf0)
Location: block/partitions/efi.c:351
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81434bf0-ffffffff81435019: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff81441fd8)
Location: block/partitions/efi.c:351
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814419c0-ffffffff81441ddc: is_gpt_valid.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff8146e948)
Location: block/partitions/efi.c:351
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8146e330-ffffffff8146e74c: is_gpt_valid.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814a25d0)
Location: block/partitions/efi.c:351
Inline: True
Inline callers:
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
Direct callers:
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
```
**Symbols:**

```
ffffffff814a2000-ffffffff814a2464: is_gpt_valid.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814bca3c)
Location: block/partitions/efi.c:351
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814bc510-ffffffff814bc974: is_gpt_valid.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814eb0be)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814eab90-ffffffff814eaffe: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff8150448a)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81503f50-ffffffff815043c1: is_gpt_valid.part.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff815648d0)
Location: block/partitions/efi.c:337
Inline: True
```
**Symbols:**

```
ffffffff815648d0-ffffffff81564cc6: is_gpt_valid.part.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff8157f9d0)
Location: block/partitions/efi.c:337
Inline: True
```
**Symbols:**

```
ffffffff8157f9d0-ffffffff8157fdc0: is_gpt_valid.part.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff81587490)
Location: block/partitions/efi.c:337
Inline: True
```
**Symbols:**

```
ffffffff81587490-ffffffff815878d5: is_gpt_valid.part.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff815ecff0)
Location: block/partitions/efi.c:335
Inline: True
```
**Symbols:**

```
ffffffff815ecff0-ffffffff815ed3e8: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8169d570)
Location: block/partitions/efi.c:335
Inline: False
```
**Symbols:**

```
ffffffff8169d570-ffffffff8169d96e: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8175bfb0)
Location: block/partitions/efi.c:335
Inline: False
```
**Symbols:**

```
ffffffff8175bfb0-ffffffff8175c398: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8179a820)
Location: block/partitions/efi.c:335
Inline: False
```
**Symbols:**

```
ffffffff8179a820-ffffffff8179ac29: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions *state, u64 lba, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff817de250)
Location: block/partitions/efi.c:335
Inline: False
```
**Symbols:**

```
ffffffff817de250-ffffffff817de659: is_gpt_valid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffff800010606678)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffff8000106060c0-ffff800010606540: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (c07b195c)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
c07b1334-c07b17d8: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (c0000000007a2720)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
Direct callers:
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:find_valid_gpt
```
**Symbols:**

```
c0000000007a1fe0-c0000000007a2594: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffe0004414da)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffe000440f90-ffffffe0004413a0: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814fca6a)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814fc530-ffffffff814fc9a1: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814ecf7a)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814eca40-ffffffff814eceb1: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff814f8afa)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814f85c0-ffffffff814f8a31: is_gpt_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (ffffffff81511b5a)
Location: block/partitions/efi.c:337
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81511620-ffffffff81511a91: is_gpt_valid.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
