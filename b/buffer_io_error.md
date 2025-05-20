# Function: <code>buffer_io_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243110)
Location: fs/buffer.c:135
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8129f827)
Location: fs/ext4/page-io.c:53
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81243110-ffffffff8124319d: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126b230)
Location: fs/buffer.c:136
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff812ce0de)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8126b230-ffffffff8126b280: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127e370)
Location: fs/buffer.c:137
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff812e3ece)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8127e370-ffffffff8127e3c0: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128bf20)
Location: fs/buffer.c:137
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff8131dabe)
Location: fs/ext4/page-io.c:54
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8128bf20-ffffffff8128bf71: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812aea10)
Location: fs/buffer.c:137
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813420ce)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812aea10-ffffffff812aea61: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:130
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff8136ff87)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812d6580-ffffffff812d65bb: buffer_io_error (STB_LOCAL)
ffffffff812dae19-ffffffff812dae35: buffer_io_error.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812f02f9)
Location: fs/buffer.c:130
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff81388417)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812eb950-ffffffff812eb98b: buffer_io_error (STB_LOCAL)
ffffffff812f02f9-ffffffff812f0315: buffer_io_error.cold.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81311be0)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813b24e8)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8130d040-ffffffff8130d07b: buffer_io_error (STB_LOCAL)
ffffffff81311be0-ffffffff81311bfc: buffer_io_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81324bed)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813cb58c)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8131ff20-ffffffff8131ff5b: buffer_io_error (STB_LOCAL)
ffffffff81324bed-ffffffff81324c09: buffer_io_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b000)
Location: fs/buffer.c:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff81417689)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368fc0)
Location: fs/buffer.c:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff8142b18a)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f500)
Location: fs/buffer.c:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff81431cfa)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be100)
Location: fs/buffer.c:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff8148554d)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445184)
Location: fs/buffer.c:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff815088b5)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d1d40)
Location: fs/buffer.c:126
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff815a33b5)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff814d1d40-ffffffff814d1dbd: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81508640)
Location: fs/buffer.c:126
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff815d9ca9)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81508640-ffffffff815086bd: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153d4b0)
Location: fs/buffer.c:127
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff81612382)
Location: fs/ext4/page-io.c:93
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8153d4b0-ffffffff8153d52d: buffer_io_error (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d78d0)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffff8000104a3418)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffff8000103d78d0-ffff8000103d7938: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b18a4)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (c0665478)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
c05b18a4-c05b1910: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dca90)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (c0000000005d0310)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
c0000000004dca90-c0000000004dcb20: buffer_io_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291448)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffe000324b02)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffe000291448-ffffffe0002914aa: buffer_io_error (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8131d1cd)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813c3b6c)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81318500-ffffffff8131853b: buffer_io_error (STB_LOCAL)
ffffffff8131d1cd-ffffffff8131d1e9: buffer_io_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8130dd6d)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813b45eb)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813090f0-ffffffff8130912b: buffer_io_error (STB_LOCAL)
ffffffff8130dd6d-ffffffff8130dd89: buffer_io_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8131ac9d)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813c0ffc)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81315fd0-ffffffff8131600b: buffer_io_error (STB_LOCAL)
ffffffff8131ac9d-ffffffff8131acb9: buffer_io_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void buffer_io_error(struct buffer_head *bh, char *msg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8132c943)
Location: fs/buffer.c:131
Inline: True
Direct callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
```
```
In fs/ext4/page-io.c (ffffffff813d6140)
Location: fs/ext4/page-io.c:55
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81327ce0-ffffffff81327d1b: buffer_io_error (STB_LOCAL)
ffffffff8132c943-ffffffff8132c95f: buffer_io_error.cold (STB_LOCAL)
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
