# Function: <code>mmap_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6e30)
Location: mm/mmap.c:1541
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811c6e30-ffffffff811c7472: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e33f0)
Location: mm/mmap.c:1432
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811e33f0-ffffffff811e3a2d: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f33d0)
Location: mm/mmap.c:1585
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811f33d0-ffffffff811f3a0d: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fe440)
Location: mm/mmap.c:1602
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811fe440-ffffffff811fea0f: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812169f0)
Location: mm/mmap.c:1618
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812169f0-ffffffff81216fc5: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812379d0)
Location: mm/mmap.c:1677
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812379d0-ffffffff81237fca: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124b360)
Location: mm/mmap.c:1701
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8124b360-ffffffff8124b9a3: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125d7c0)
Location: mm/mmap.c:1703
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8125d7c0-ffffffff8125de2e: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126bf90)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8126bf90-ffffffff8126c5fe: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129bcb0)
Location: mm/mmap.c:1687
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8129bcb0-ffffffff8129c3a8: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6f60)
Location: mm/mmap.c:1726
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812a6f60-ffffffff812a76da: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812acd30)
Location: mm/mmap.c:1730
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812acd30-ffffffff812ad3dc: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ee480)
Location: mm/mmap.c:1716
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812ee480-ffffffff812eead6: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351870)
Location: mm/mmap.c:1729
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81351870-ffffffff81351ebc: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cb550)
Location: mm/mmap.c:2519
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff813cb550-ffffffff813cbe5a: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ffe00)
Location: mm/mmap.c:2640
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff813ffe00-ffffffff8140077c: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142c360)
Location: mm/mmap.c:2722
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8142c360-ffffffff8142cdba: mmap_region (STB_GLOBAL)
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
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010303370)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffff800010303370-ffff800010303998: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0521a30)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
c0521a30-c05220cc: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cfdb0)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
c0000000003cfdb0-c0000000003d0524: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ff56)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffe00020ff56-ffffffe0002103bc: mmap_region (STB_GLOBAL)
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
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812645e0)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812645e0-ffffffff81264c4e: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81256a00)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81256a00-ffffffff8125706e: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262380)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81262380-ffffffff812629ee: mmap_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mmap_region(struct file *file, long unsigned int addr, long unsigned int len, vm_flags_t vm_flags, long unsigned int pgoff, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81271d40)
Location: mm/mmap.c:1711
Inline: False
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81271d40-ffffffff812723ae: mmap_region (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct list_head *uf</code>
</li>
</ul>
</details>
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
