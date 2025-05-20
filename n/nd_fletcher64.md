# Function: <code>nd_fletcher64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815968f0)
Location: drivers/nvdimm/core.c:59
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff815968f0-ffffffff8159692d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815eb6d0)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff815eb6d0-ffffffff815eb70d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816184e0)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff816184e0-ffffffff8161851d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162c360)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8162c360-ffffffff8162c39d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81695000)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81695000-ffffffff8169503d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d10d0)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff816d10d0-ffffffff816d110d: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2770)
Location: drivers/nvdimm/core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff816f2770-ffffffff816f27ad: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172bcf0)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8172bcf0-ffffffff8172bd2f: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8174ff40)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8174ff40-ffffffff8174ff7f: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180e690)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8180e690-ffffffff8180e6d0: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181d1e0)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8181d1e0-ffffffff8181d220: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81800570)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81800570-ffffffff818005ad: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188a970)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8188a970-ffffffff8188a9ad: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d3cf0)
Location: drivers/nvdimm/core.c:180
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff819d3cf0-ffffffff819d3d42: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4e430)
Location: drivers/nvdimm/core.c:180
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81b4e430-ffffffff81b4e482: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba1890)
Location: drivers/nvdimm/core.c:180
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81ba1890-ffffffff81ba18e2: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf5a20)
Location: drivers/nvdimm/core.c:180
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81bf5a20-ffffffff81bf5a72: nd_fletcher64 (STB_GLOBAL)
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
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff80001094fb08)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffff80001094fb08-ffff80001094fb70: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fc240)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
c0000000009fc240-c0000000009fc298: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005bffb8)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffe0005bffb8-ffffffe0005c000a: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81704630)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81704630-ffffffff8170466f: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d80b0)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff816d80b0-ffffffff816d80ef: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81743400)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff81743400-ffffffff8174343f: nd_fletcher64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 nd_fletcher64(void *addr, size_t len, bool le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175e850)
Location: drivers/nvdimm/core.c:179
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__nd_label_validate
  - drivers/nvdimm/claim.c:nd_sb_checksum
```
**Symbols:**

```
ffffffff8175e850-ffffffff8175e88f: nd_fletcher64 (STB_GLOBAL)
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
