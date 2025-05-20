# Function: <code>compat_rw_copy_check_uvector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81264950)
Location: fs/compat.c:546
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff81264950-ffffffff81264ae4: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81290c80)
Location: fs/compat.c:546
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff81290c80-ffffffff81290dd3: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a5ae0)
Location: fs/compat.c:493
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812a5ae0-ffffffff812a5c42: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81252680)
Location: fs/read_write.c:823
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff81252680-ffffffff812527c8: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812744d0)
Location: fs/read_write.c:828
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812744d0-ffffffff81274623: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129b340)
Location: fs/read_write.c:855
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff8129b340-ffffffff8129b4a0: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812b0240)
Location: fs/read_write.c:852
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812b0240-ffffffff812b03a0: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ccb90)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812ccb90-ffffffff812cccbf: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812de5b0)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812de5b0-ffffffff812de6df: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81315310)
Location: fs/read_write.c:894
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff81315310-ffffffff8131545f: compat_rw_copy_check_uvector (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff8000103848b0)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffff8000103848b0-ffff800010384c88: compat_rw_copy_check_uvector (STB_GLOBAL)
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
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047aa20)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
c00000000047aa20-c00000000047ac6c: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
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

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6b90)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812d6b90-ffffffff812d6cbf: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7810)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812c7810-ffffffff812c793f: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d49a0)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812d49a0-ffffffff812d4acf: compat_rw_copy_check_uvector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t compat_rw_copy_check_uvector(int type, const struct compat_iovec *uvector, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_pointer, struct iovec **ret_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5800)
Location: fs/read_write.c:866
Inline: False
Direct callers:
  - mm/process_vm_access.c:compat_process_vm_rw
  - lib/iov_iter.c:compat_import_iovec
```
**Symbols:**

```
ffffffff812e5800-ffffffff812e592f: compat_rw_copy_check_uvector (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
