# Function: <code>ext4_convert_unwritten_extents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c9730)
Location: fs/ext4/extents.c:5026
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_end_io_unwritten
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_put_io_end
```
**Symbols:**

```
ffffffff812c9730-ffffffff812c98e9: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f9010)
Location: fs/ext4/extents.c:5028
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff812f9010-ffffffff812f91cf: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130f010)
Location: fs/ext4/extents.c:5008
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff8130f010-ffffffff8130f1cf: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812ed550)
Location: fs/ext4/extents.c:5004
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff812ed550-ffffffff812ed719: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81312010)
Location: fs/ext4/extents.c:5007
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81312010-ffffffff813121d9: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133fec0)
Location: fs/ext4/extents.c:5003
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff8133fec0-ffffffff8134008e: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81357430)
Location: fs/ext4/extents.c:4902
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81357430-ffffffff81357666: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81380da0)
Location: fs/ext4/extents.c:4912
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81380da0-ffffffff81380fd3: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81399490)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81399490-ffffffff813996c3: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e5340)
Location: fs/ext4/extents.c:4722
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff813e5340-ffffffff813e555a: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6b60)
Location: fs/ext4/extents.c:4731
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff813f6b60-ffffffff813f6d7a: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fcf00)
Location: fs/ext4/extents.c:4737
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff813fcf00-ffffffff813fd117: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4775
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff81cc97f4-ffffffff81cc98a1: ext4_convert_unwritten_extents.cold (STB_LOCAL)
ffffffff8144f2e0-ffffffff8144f50e: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4778
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff81e7c504-ffffffff81e7c5b2: ext4_convert_unwritten_extents.cold (STB_LOCAL)
ffffffff814cc090-ffffffff814cc313: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4782
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff8206cb4e-ffffffff8206cbfc: ext4_convert_unwritten_extents.cold (STB_LOCAL)
ffffffff81564770-ffffffff815649f6: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4781
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff820ec8c8-ffffffff820ec974: ext4_convert_unwritten_extents.cold (STB_LOCAL)
ffffffff8159c420-ffffffff8159c69e: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4816
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_io_end_vec
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff821c9b04-ffffffff821c9bb0: ext4_convert_unwritten_extents.cold (STB_LOCAL)
ffffffff815d50d0-ffffffff815d534e: ext4_convert_unwritten_extents (STB_GLOBAL)
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
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046be50)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffff80001046be50-ffff80001046c0ac: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062cff8)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
c062cff8-c062d290: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058b5a0)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
c00000000058b5a0-c00000000058b910: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f9456)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffe0002f9456-ffffffe0002f968e: ext4_convert_unwritten_extents (STB_GLOBAL)
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
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391a70)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81391a70-ffffffff81391ca3: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81382500)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81382500-ffffffff81382733: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138f3d0)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff8138f3d0-ffffffff8138f603: ext4_convert_unwritten_extents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents(handle_t *handle, struct inode *inode, loff_t offset, ssize_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a31f0)
Location: fs/ext4/extents.c:4958
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813a31f0-ffffffff813a3423: ext4_convert_unwritten_extents (STB_GLOBAL)
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
