# Function: <code>filemap_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filemap_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f760)
Location: mm/filemap.c:1931
Inline: False
```
**Symbols:**

```
ffffffff8118f760-ffffffff8118fb4e: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filemap_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a3560)
Location: mm/filemap.c:2075
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff811a3560-ffffffff811a3aec: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filemap_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b3740)
Location: mm/filemap.c:2191
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff811b3740-ffffffff811b3e54: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ba560)
Location: mm/filemap.c:2325
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff811ba560-ffffffff811bab39: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cddc0)
Location: mm/filemap.c:2495
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff811cddc0-ffffffff811ce4a4: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef900)
Location: mm/filemap.c:2492
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff811ef900-ffffffff811f0051: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201b50)
Location: mm/filemap.c:2480
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff81201b50-ffffffff812023f0: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812176f0)
Location: mm/filemap.c:2517
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff812176f0-ffffffff812181b1: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225010)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff81225010-ffffffff81225a50: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253020)
Location: mm/filemap.c:2478
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff81253020-ffffffff812537ae: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125dbf0)
Location: mm/filemap.c:2793
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff8125dbf0-ffffffff8125e42f: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812609d0)
Location: mm/filemap.c:2959
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff812609d0-ffffffff81261206: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d3c0)
Location: mm/filemap.c:3040
Inline: False
```
**Symbols:**

```
ffffffff8129d3c0-ffffffff8129de6c: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f4520)
Location: mm/filemap.c:3112
Inline: False
```
**Symbols:**

```
ffffffff812f4520-ffffffff812f4e29: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135e600)
Location: mm/filemap.c:3119
Inline: False
```
**Symbols:**

```
ffffffff8135e600-ffffffff8135ece4: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813913a0)
Location: mm/filemap.c:3263
Inline: False
```
**Symbols:**

```
ffffffff813913a0-ffffffff81391b27: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bb100)
Location: mm/filemap.c:3211
Inline: False
```
**Symbols:**

```
ffffffff813bb100-ffffffff813bb9db: filemap_fault (STB_GLOBAL)
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
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b2338)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffff8000102b2338-ffff8000102b2ad8: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04df27c)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
c04df27c-c04dfd54: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000368790)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
c000000000368790-c0000000003694ac: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d7c68)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffe0001d7c68-ffffffe0001d8404: filemap_fault (STB_GLOBAL)
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
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121d660)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff8121d660-ffffffff8121e0a0: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81210830)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff81210830-ffffffff81211256: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b400)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff8121b400-ffffffff8121be40: filemap_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t filemap_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122a460)
Location: mm/filemap.c:2476
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_filemap_fault
```
**Symbols:**

```
ffffffff8122a460-ffffffff8122ae85: filemap_fault (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf</code> ➡️ <code>vmf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
