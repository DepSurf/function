# Function: <code>compare_gpts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff813d3fe0)
Location: block/partitions/efi.c:490
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff813d3fe0-ffffffff813d4256: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff81419af0)
Location: block/partitions/efi.c:490
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81419af0-ffffffff81419d66: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff81435020)
Location: block/partitions/efi.c:490
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81435020-ffffffff81435296: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff81441730)
Location: block/partitions/efi.c:497
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81441730-ffffffff814419ba: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8146e0a0)
Location: block/partitions/efi.c:497
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff8146e0a0-ffffffff8146e32a: compare_gpts (STB_LOCAL)
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
In block/partitions/efi.c (ffffffff814a26af)
Location: block/partitions/efi.c:497
Inline: True
Inline callers:
  - block/partitions/efi.c:find_valid_gpt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:497
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814bc3c0-ffffffff814bc50a: compare_gpts (STB_LOCAL)
ffffffff814bd05e-ffffffff814bd19e: compare_gpts.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814eaa40-ffffffff814eab8a: compare_gpts (STB_LOCAL)
ffffffff814eb708-ffffffff814eb84a: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff81503e00-ffffffff81503f4a: compare_gpts (STB_LOCAL)
ffffffff81504acd-ffffffff81504c0f: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
```
**Symbols:**

```
ffffffff815644b0-ffffffff815645f6: compare_gpts (STB_LOCAL)
ffffffff81565400-ffffffff81565542: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
```
**Symbols:**

```
ffffffff8157f5d0-ffffffff8157f716: compare_gpts (STB_LOCAL)
ffffffff81bf3542-ffffffff81bf3684: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
```
**Symbols:**

```
ffffffff81587110-ffffffff8158725a: compare_gpts (STB_LOCAL)
ffffffff81be5542-ffffffff81be5684: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:481
Inline: False
```
**Symbols:**

```
ffffffff815ecc90-ffffffff815ecdda: compare_gpts (STB_LOCAL)
ffffffff81cd998b-ffffffff81cd9acd: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:481
Inline: False
```
**Symbols:**

```
ffffffff8169d1c0-ffffffff8169d31c: compare_gpts (STB_LOCAL)
ffffffff81e8d416-ffffffff81e8d55f: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8175bb00)
Location: block/partitions/efi.c:481
Inline: False
```
**Symbols:**

```
ffffffff8175bb00-ffffffff8175bde8: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff8179a1a0)
Location: block/partitions/efi.c:481
Inline: False
```
**Symbols:**

```
ffffffff8179a1a0-ffffffff8179a488: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffff817ddbd0)
Location: block/partitions/efi.c:481
Inline: False
```
**Symbols:**

```
ffffffff817ddbd0-ffffffff817ddeb8: compare_gpts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffff800010605c78)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffff800010605c78-ffff800010605ef8: compare_gpts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (c07b0fd8)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
c07b0fd8-c07b1334: compare_gpts (STB_LOCAL)
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
In block/partitions/efi.c (c0000000007a2828)
Location: block/partitions/efi.c:483
Inline: True
Inline callers:
  - block/partitions/efi.c:find_valid_gpt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/efi.c (ffffffe0004406fc)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffe0004406fc-ffffffe000440f2a: compare_gpts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814fc3e0-ffffffff814fc52a: compare_gpts (STB_LOCAL)
ffffffff814fd0ad-ffffffff814fd1ef: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814ec8f0-ffffffff814eca3a: compare_gpts (STB_LOCAL)
ffffffff814ed5bd-ffffffff814ed6ff: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff814f8470-ffffffff814f85ba: compare_gpts (STB_LOCAL)
ffffffff814f913d-ffffffff814f927f: compare_gpts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void compare_gpts(gpt_header *pgpt, gpt_header *agpt, u64 lastlba);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/efi.c (0)
Location: block/partitions/efi.c:483
Inline: False
Direct callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
```
**Symbols:**

```
ffffffff815114d0-ffffffff8151161a: compare_gpts (STB_LOCAL)
ffffffff8151219d-ffffffff815122df: compare_gpts.cold (STB_LOCAL)
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
