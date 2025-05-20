# Function: <code>memcpy_mcsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - fs/dax.c:read_dax_sector
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8143e210-ffffffff8143e2c3: memcpy_mcsafe (STB_GLOBAL)
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
In fs/dax.c (ffffffff8129b284)
Location: arch/x86/include/asm/string_64.h:100
Inline: True
Inline callers:
  - fs/dax.c:read_dax_sector
```
```
In drivers/nvdimm/claim.c (ffffffff81624f2f)
Location: arch/x86/include/asm/string_64.h:100
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In drivers/nvdimm/claim.c (ffffffff81639ee9)
Location: arch/x86/include/asm/string_64.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In drivers/nvdimm/claim.c (ffffffff816a2ae9)
Location: arch/x86/include/asm/string_64.h:137
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff814c7e78)
Location: arch/x86/include/asm/string_64.h:139
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff816dec7d)
Location: arch/x86/include/asm/string_64.h:139
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff814dc76c)
Location: arch/x86/include/asm/string_64.h:121
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8170104d)
Location: arch/x86/include/asm/string_64.h:121
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff81508128)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8173aebd)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff81526248)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8175eb8d)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81589b61)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8181e58e)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/nvdimm/claim.c (ffff80001096036c)
Location: include/linux/string.h:164
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:copyout_mcsafe
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c0000000000b3d10-c0000000000b3d10: memcpy_mcsafe (STB_GLOBAL)
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
In drivers/nvdimm/claim.c (ffffffe0005cde2a)
Location: include/linux/string.h:164
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff8151e828)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8171327d)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff8150eb18)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff816e6cfd)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb73a)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
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
In lib/iov_iter.c (ffffffff8151a8b8)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8175204d)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
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
In lib/iov_iter.c (ffffffff815340e8)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:memcpy_mcsafe_to_page
```
```
In drivers/nvdimm/claim.c (ffffffff8176d4cd)
Location: arch/x86/include/asm/string_64.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
</details>
</li>
</ul>

## Differences
