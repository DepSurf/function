# Function: <code>fuse_send_readpages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81316820)
Location: fs/fuse/file.c:798
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81316820-ffffffff81316937: fuse_send_readpages.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8134b520)
Location: fs/fuse/file.c:811
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8134b520-ffffffff8134b637: fuse_send_readpages.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81360e30)
Location: fs/fuse/file.c:812
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81360e30-ffffffff81360f47: fuse_send_readpages.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81375470)
Location: fs/fuse/file.c:807
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81375470-ffffffff81375587: fuse_send_readpages.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8139a600)
Location: fs/fuse/file.c:810
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8139a600-ffffffff8139a71a: fuse_send_readpages.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813c9820)
Location: fs/fuse/file.c:810
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff813c9820-ffffffff813c993d: fuse_send_readpages.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813e24d0)
Location: fs/fuse/file.c:815
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff813e24d0-ffffffff813e25ed: fuse_send_readpages.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140e190)
Location: fs/fuse/file.c:827
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8140e190-ffffffff8140e2c0: fuse_send_readpages.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81427300)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81427300-ffffffff8142742d: fuse_send_readpages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_send_readpages(struct fuse_io_args *ia, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477ca0)
Location: fs/fuse/file.c:899
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81477ca0-ffffffff81477e0a: fuse_send_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_send_readpages(struct fuse_io_args *ia, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492540)
Location: fs/fuse/file.c:922
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readahead
```
**Symbols:**

```
ffffffff81492540-ffffffff814926af: fuse_send_readpages (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8149764b)
Location: fs/fuse/file.c:917
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In fs/fuse/file.c (ffffffff814ef1af)
Location: fs/fuse/file.c:921
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In fs/fuse/file.c (ffffffff8157ef22)
Location: fs/fuse/file.c:931
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81624be3)
Location: fs/fuse/file.c:931
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165cf86)
Location: fs/fuse/file.c:932
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81696ce3)
Location: fs/fuse/file.c:933
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
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
In fs/fuse/file.c (ffff80001050bd50)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffff80001050bd50-ffff80001050beb8: fuse_send_readpages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_send_readpages(struct fuse_io_args *ia, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c701c)
Location: fs/fuse/file.c:882
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
c06c701c-c06c7134: fuse_send_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_send_readpages(struct fuse_io_args *ia, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006518a0)
Location: fs/fuse/file.c:882
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
c0000000006518a0-c000000000651a64: fuse_send_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_send_readpages(struct fuse_io_args *ia, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe0003765ac)
Location: fs/fuse/file.c:882
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffe0003765ac-ffffffe0003766d4: fuse_send_readpages (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8141f8e0)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8141f8e0-ffffffff8141fa0d: fuse_send_readpages.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81410360)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81410360-ffffffff8141048d: fuse_send_readpages.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8141ba80)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8141ba80-ffffffff8141bbad: fuse_send_readpages.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81432ff0)
Location: fs/fuse/file.c:882
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81432ff0-ffffffff8143311d: fuse_send_readpages.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
