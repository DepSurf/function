# Function: <code>__memcpy_mcsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff819e0f00-ffffffff819e0f5b: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81a1beb0-ffffffff81a1bf0a: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81a8bc80-ffffffff81a8bcda: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81ac2f40-ffffffff81ac2f9a: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff815ff490-ffffffff815ff4ea: __memcpy_mcsafe (STB_GLOBAL)
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81a61d90-ffffffff81a61dea: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

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
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81a1ee00-ffffffff81a1ee5a: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81ace180-ffffffff81ace1da: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

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
  - arch/x86/lib/usercopy_64.c:mcsafe_handle_tail
```
**Symbols:**

```
ffffffff81ada690-ffffffff81ada6ea: __memcpy_mcsafe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
