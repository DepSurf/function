# Function: <code>do_sync_mmap_readahead</code>

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
In mm/filemap.c (ffffffff8118fa50)
Location: mm/filemap.c:1846
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff811a39b6)
Location: mm/filemap.c:1990
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff811b3d12)
Location: mm/filemap.c:2106
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff811ba836)
Location: mm/filemap.c:2241
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff811cdff1)
Location: mm/filemap.c:2411
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff811efb7d)
Location: mm/filemap.c:2408
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff81201dd7)
Location: mm/filemap.c:2396
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff81217cd2)
Location: mm/filemap.c:2424
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff812255a5)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *do_sync_mmap_readahead(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124f020)
Location: mm/filemap.c:2385
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff8124f020-ffffffff8124f18d: do_sync_mmap_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *do_sync_mmap_readahead(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812596c0)
Location: mm/filemap.c:2696
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff812596c0-ffffffff81259873: do_sync_mmap_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260e35)
Location: mm/filemap.c:2862
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d8a0)
Location: mm/filemap.c:2943
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f4927)
Location: mm/filemap.c:2996
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *do_sync_mmap_readahead(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135b280)
Location: mm/filemap.c:3003
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff8135b280-ffffffff8135b4e6: do_sync_mmap_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *do_sync_mmap_readahead(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138d0e0)
Location: mm/filemap.c:3147
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff8138d0e0-ffffffff8138d34f: do_sync_mmap_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *do_sync_mmap_readahead(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b6c50)
Location: mm/filemap.c:3095
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
```
**Symbols:**

```
ffffffff813b6c50-ffffffff813b6f34: do_sync_mmap_readahead (STB_LOCAL)
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
In mm/filemap.c (ffff8000102b2770)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (c04df9e8)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (c000000000368d58)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffe0001d809e)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff8121dbf5)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff81210dab)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff8121b995)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
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
In mm/filemap.c (ffffffff8122a9f6)
Location: mm/filemap.c:2383
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
