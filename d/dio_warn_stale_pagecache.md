# Function: <code>dio_warn_stale_pagecache</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff812df230)
Location: fs/direct-io.c:225
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff812de040-ffffffff812de086: dio_warn_stale_pagecache.part.20 (STB_LOCAL)
ffffffff812e2360-ffffffff812e23b6: dio_warn_stale_pagecache.part.20.cold.23 (STB_LOCAL)
ffffffff812df230-ffffffff812df27a: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff812f3d00)
Location: fs/direct-io.c:225
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff812f36e0-ffffffff812f3726: dio_warn_stale_pagecache.part.22 (STB_LOCAL)
ffffffff812f6fa0-ffffffff812f6ff6: dio_warn_stale_pagecache.part.22.cold.25 (STB_LOCAL)
ffffffff812f3d00-ffffffff812f3d47: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff81315690)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81315110-ffffffff81315157: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff81317580-ffffffff813175d7: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff81315690-ffffffff813156d9: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff81328510)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81327f90-ffffffff81327fd7: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff8132a400-ffffffff8132a457: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff81328510-ffffffff81328559: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81251430)
Location: mm/filemap.c:3155
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff8124e3b0-ffffffff8124e3f7: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff812540fb-ffffffff8125414d: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff812540b0-ffffffff812540fb: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8125cbf9)
Location: mm/filemap.c:3250
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff812587d0-ffffffff81258817: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff81be699b-ffffffff81be69ed: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff8125ebb0-ffffffff8125ebfd: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8126187a)
Location: mm/filemap.c:3497
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff8125ce30-ffffffff8125ce77: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff81bd8731-ffffffff81bd8783: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff81263730-ffffffff8126377a: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8129a170)
Location: mm/filemap.c:3614
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81298db0-ffffffff81298df7: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff81cb9d88-ffffffff81cb9dda: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff8129fef0-ffffffff8129ff3d: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:3642
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81e6b7b9-ffffffff81e6b7f6: dio_warn_stale_pagecache.cold (STB_LOCAL)
ffffffff812f6ff0-ffffffff812f70a8: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81360830)
Location: mm/filemap.c:3636
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81360830-ffffffff8136091b: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b8e0)
Location: mm/filemap.c:3804
Inline: False
```
**Symbols:**

```
ffffffff8138b8e0-ffffffff8138b9cb: dio_warn_stale_pagecache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b53c0)
Location: mm/filemap.c:3811
Inline: False
```
**Symbols:**

```
ffffffff813b53c0-ffffffff813b54ab: dio_warn_stale_pagecache (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffff8000103e31b8)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffff8000103e31b8-ffff8000103e3250: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffff8000103e3990-ffff8000103e39ec: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (c05bb0b4)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
c05bb0b4-c05bb158: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
c05bb6f0-c05bb744: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (c0000000004e8fe0)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
c0000000004e8fe0-c0000000004e9094: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
c0000000004e9800-c0000000004e9888: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffe0002993e2)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffe0002993e2-ffffffe00029944e: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffe0002998dc-ffffffe000299934: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff81320af0)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81320570-ffffffff813205b7: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff813229e0-ffffffff81322a37: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff81320af0-ffffffff81320b39: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff81311690)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff81311110-ffffffff81311157: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff81313580-ffffffff813135d7: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff81311690-ffffffff813116d9: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff8131e5c0)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff8131e040-ffffffff8131e087: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff813204b0-ffffffff81320507: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff8131e5c0-ffffffff8131e609: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dio_warn_stale_pagecache(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (ffffffff813302c0)
Location: fs/direct-io.c:226
Inline: True
Direct callers:
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
**Symbols:**

```
ffffffff8132fd40-ffffffff8132fd87: dio_warn_stale_pagecache.part.0 (STB_LOCAL)
ffffffff813321d0-ffffffff81332227: dio_warn_stale_pagecache.part.0.cold (STB_LOCAL)
ffffffff813302c0-ffffffff81330309: dio_warn_stale_pagecache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
