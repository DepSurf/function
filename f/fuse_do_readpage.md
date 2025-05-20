# Function: <code>fuse_do_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81316bd0)
Location: fs/fuse/file.c:699
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_write_begin
```
**Symbols:**

```
ffffffff81316bd0-ffffffff81316d9d: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134ae50)
Location: fs/fuse/file.c:712
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff8134ae50-ffffffff8134b028: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81360760)
Location: fs/fuse/file.c:713
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81360760-ffffffff81360938: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81375800)
Location: fs/fuse/file.c:708
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81375800-ffffffff813759c8: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81399fb0)
Location: fs/fuse/file.c:708
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81399fb0-ffffffff8139a112: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cadc0)
Location: fs/fuse/file.c:708
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff813cadc0-ffffffff813cafef: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e2870)
Location: fs/fuse/file.c:713
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff813e2870-ffffffff813e29cc: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140e540)
Location: fs/fuse/file.c:725
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff8140e540-ffffffff8140e6b8: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81427430)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81427430-ffffffff814275e3: fuse_do_readpage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477f40)
Location: fs/fuse/file.c:798
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81477f40-ffffffff8147810a: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814926b0)
Location: fs/fuse/file.c:821
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff814926b0-ffffffff8149287d: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814977d0)
Location: fs/fuse/file.c:816
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff814977d0-ffffffff8149799d: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ef3e0)
Location: fs/fuse/file.c:820
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff814ef3e0-ffffffff814ef5ad: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157e7b0)
Location: fs/fuse/file.c:829
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_read_folio
```
**Symbols:**

```
ffffffff8157e7b0-ffffffff8157e99a: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81624120)
Location: fs/fuse/file.c:829
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_read_folio
```
**Symbols:**

```
ffffffff81624120-ffffffff8162432a: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165c7e0)
Location: fs/fuse/file.c:830
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_read_folio
```
**Symbols:**

```
ffffffff8165c7e0-ffffffff8165c9ec: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81696540)
Location: fs/fuse/file.c:831
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_read_folio
```
**Symbols:**

```
ffffffff81696540-ffffffff8169674c: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffff80001050c158)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffff80001050c158-ffff80001050c31c: fuse_do_readpage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6cc0)
Location: fs/fuse/file.c:781
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
c06c6cc0-c06c6e3c: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000651a70)
Location: fs/fuse/file.c:781
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
c000000000651a70-c000000000651c60: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_do_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003768f4)
Location: fs/fuse/file.c:781
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffe0003768f4-ffffffe000376a46: fuse_do_readpage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141fa10)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff8141fa10-ffffffff8141fbc3: fuse_do_readpage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81410490)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81410490-ffffffff81410643: fuse_do_readpage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141bbb0)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff8141bbb0-ffffffff8141bd63: fuse_do_readpage.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81432a40)
Location: fs/fuse/file.c:781
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81432a40-ffffffff81432bf3: fuse_do_readpage.isra.0 (STB_LOCAL)
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
</ul>
