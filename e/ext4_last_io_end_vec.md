# Function: <code>ext4_last_io_end_vec</code>

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
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814179e0)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff814179e0-ffffffff814179fe: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142b4e0)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff8142b4e0-ffffffff8142b4fe: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81431eb0)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81431eb0-ffffffff81431ece: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81485700)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff81485700-ffffffff8148571e: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81508b90)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff81508b90-ffffffff81508bb6: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a36e0)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff815a36e0-ffffffff815a3706: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815da170)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_folio
```
**Symbols:**

```
ffffffff815da170-ffffffff815da196: ext4_last_io_end_vec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ext4_io_end_vec *ext4_last_io_end_vec(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81612930)
Location: fs/ext4/page-io.c:80
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_process_folio
```
**Symbols:**

```
ffffffff81612930-ffffffff81612956: ext4_last_io_end_vec (STB_GLOBAL)
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
