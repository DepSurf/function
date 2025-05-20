# Function: <code>follow_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bc390)
Location: mm/memory.c:3584
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811bc390-ffffffff811bc41b: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d6e60)
Location: mm/memory.c:3779
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811d6e60-ffffffff811d6eeb: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6bb0)
Location: mm/memory.c:3857
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811e6bb0-ffffffff811e6c3d: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1dc0)
Location: mm/memory.c:4147
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff811f1dc0-ffffffff811f1e51: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208be0)
Location: mm/memory.c:4325
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81208be0-ffffffff81208c81: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229bc0)
Location: mm/memory.c:4370
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81229bc0-ffffffff81229c67: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123d080)
Location: mm/memory.c:4160
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8123d080-ffffffff8123d124: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ed20)
Location: mm/memory.c:4211
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8124ed20-ffffffff8124edc7: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d300)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8125d300-ffffffff8125d3a7: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128d8e0)
Location: mm/memory.c:4601
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff8128d8e0-ffffffff8128d986: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129fdb0)
Location: mm/memory.c:4829
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff8129fdb0-ffffffff8129fe56: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5610)
Location: mm/memory.c:4856
Inline: False
```
**Symbols:**

```
ffffffff812a5610-ffffffff812a56ba: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6b00)
Location: mm/memory.c:5002
Inline: False
```
**Symbols:**

```
ffffffff812e6b00-ffffffff812e6baa: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133ea00)
Location: mm/memory.c:5309
Inline: False
```
**Symbols:**

```
ffffffff8133ea00-ffffffff8133eac0: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b6980)
Location: mm/memory.c:5389
Inline: False
```
**Symbols:**

```
ffffffff813b6980-ffffffff813b6a40: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eb340)
Location: mm/memory.c:5580
Inline: False
```
**Symbols:**

```
ffffffff813eb340-ffffffff813eb400: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417180)
Location: mm/memory.c:5806
Inline: False
```
**Symbols:**

```
ffffffff81417180-ffffffff81417245: follow_pfn (STB_GLOBAL)
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
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f47e8)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffff8000102f47e8-ffff8000102f4890: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0516978)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
c0516978-c0516a34: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bb490)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
c0000000003bb490-c0000000003bb58c: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002068ae)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffe0002068ae-ffffffe000206962: follow_pfn (STB_GLOBAL)
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
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255950)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81255950-ffffffff812559f7: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81248040)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff81248040-ffffffff812480e0: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812536f0)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff812536f0-ffffffff81253797: follow_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_pfn(struct vm_area_struct *vma, long unsigned int address, long unsigned int *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812630c0)
Location: mm/memory.c:4236
Inline: False
Direct callers:
  - mm/frame_vector.c:get_vaddr_frames
```
**Symbols:**

```
ffffffff812630c0-ffffffff81263169: follow_pfn (STB_GLOBAL)
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
