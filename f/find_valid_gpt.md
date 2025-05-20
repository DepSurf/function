# Function: <code>find_valid_gpt</code>

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
In block/partitions/efi.c (ffffffff813d42bd)
Location: block/partitions/efi.c:590
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff81419dcd)
Location: block/partitions/efi.c:590
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff814352fd)
Location: block/partitions/efi.c:590
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff81441e55)
Location: block/partitions/efi.c:597
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff8146e7c5)
Location: block/partitions/efi.c:597
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int find_valid_gpt(struct parsed_partitions *state, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:597
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814a2470-ffffffff814a29ce: find_valid_gpt (STB_LOCAL)
ffffffff814a2d73-ffffffff814a2fdd: find_valid_gpt.cold.8 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff814bca12)
Location: block/partitions/efi.c:597
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff814eb094)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff81504460)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:583
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81564cd0-ffffffff81565062: find_valid_gpt.constprop.0 (STB_LOCAL)
ffffffff81565542-ffffffff81565558: find_valid_gpt.constprop.0.cold (STB_LOCAL)
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
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:583
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8157fdc0-ffffffff81580167: find_valid_gpt.constprop.0 (STB_LOCAL)
ffffffff81bf3684-ffffffff81bf369a: find_valid_gpt.constprop.0.cold (STB_LOCAL)
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
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:583
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff815878e0-ffffffff81587cd5: find_valid_gpt.constprop.0 (STB_LOCAL)
ffffffff81be5684-ffffffff81be569a: find_valid_gpt.constprop.0.cold (STB_LOCAL)
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
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:581
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff815ed3f0-ffffffff815ed98b: find_valid_gpt.constprop.0 (STB_LOCAL)
ffffffff81cd9acd-ffffffff81cd9ade: find_valid_gpt.constprop.0.cold (STB_LOCAL)
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
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:581
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8169d970-ffffffff8169df3a: find_valid_gpt.constprop.0 (STB_LOCAL)
ffffffff81e8d55f-ffffffff81e8d570: find_valid_gpt.constprop.0.cold (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff8175c3b0)
Location: block/partitions/efi.c:581
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8175c3b0-ffffffff8175c96e: find_valid_gpt.constprop.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff8179ac40)
Location: block/partitions/efi.c:581
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8179ac40-ffffffff8179b20e: find_valid_gpt.constprop.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff817de670)
Location: block/partitions/efi.c:581
Inline: True
Direct callers:
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff817de670-ffffffff817dec6d: find_valid_gpt.constprop.0 (STB_LOCAL)
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
In block/partitions/efi.c (ffff8000106065a8)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (c07b1830)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int find_valid_gpt(struct parsed_partitions *state, gpt_header **gpt, gpt_entry **ptes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (c0000000007a25a0)
Location: block/partitions/efi.c:583
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
c0000000007a25a0-c0000000007a2db4: find_valid_gpt (STB_LOCAL)
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
In block/partitions/efi.c (ffffffe0004413de)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff814fca40)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff814ecf50)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff814f8ad0)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
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
In block/partitions/efi.c (ffffffff81511b30)
Location: block/partitions/efi.c:583
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
