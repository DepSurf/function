# Function: <code>iomap_submit_ioend</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa040)
Location: fs/iomap/buffered-io.c:1223
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813aa040-ffffffff813aa0bc: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb690)
Location: fs/iomap/buffered-io.c:1193
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813bb690-ffffffff813bb70c: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c27b0)
Location: fs/iomap/buffered-io.c:1190
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813c27b0-ffffffff813c282c: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff814120d0)
Location: fs/iomap/buffered-io.c:1159
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff814120d0-ffffffff8141214c: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81488020)
Location: fs/iomap/buffered-io.c:1186
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff81488020-ffffffff814880ac: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151bc80)
Location: fs/iomap/buffered-io.c:1447
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff8151bc80-ffffffff8151bd0c: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81553f90)
Location: fs/iomap/buffered-io.c:1467
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff81553f90-ffffffff8155401c: iomap_submit_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_submit_ioend(struct iomap_writepage_ctx *wpc, struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81589f70)
Location: fs/iomap/buffered-io.c:1635
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepages
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff81589f70-ffffffff81589ffc: iomap_submit_ioend (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
