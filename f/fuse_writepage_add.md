# Function: <code>fuse_writepage_add</code>

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
bool fuse_writepage_add(struct fuse_writepage_args *new_wpa, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814773d0)
Location: fs/fuse/file.c:1970
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff814773d0-ffffffff81477583: fuse_writepage_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fuse_writepage_add(struct fuse_writepage_args *new_wpa, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814935f0)
Location: fs/fuse/file.c:2010
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff814935f0-ffffffff814937bd: fuse_writepage_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fuse_writepage_add(struct fuse_writepage_args *new_wpa, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81498580)
Location: fs/fuse/file.c:2021
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff81498580-ffffffff8149874a: fuse_writepage_add (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff814f3853)
Location: fs/fuse/file.c:2050
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In fs/fuse/file.c (ffffffff815832bb)
Location: fs/fuse/file.c:2069
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In fs/fuse/file.c (ffffffff8162924b)
Location: fs/fuse/file.c:2104
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In fs/fuse/file.c (ffffffff81661460)
Location: fs/fuse/file.c:2081
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In fs/fuse/file.c (ffffffff8169b320)
Location: fs/fuse/file.c:2101
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
</ul>
