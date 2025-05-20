# Function: <code>fs_lookup_param</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8130af20)
Location: fs/fs_parser.c:239
Inline: False
```
**Symbols:**

```
ffffffff8130af20-ffffffff8130b060: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8131def0)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffff8131def0-ffffffff8131e030: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81357c90)
Location: fs/fs_parser.c:143
Inline: False
```
**Symbols:**

```
ffffffff81357c90-ffffffff81357dd7: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813646e0)
Location: fs/fs_parser.c:143
Inline: False
```
**Symbols:**

```
ffffffff813646e0-ffffffff81364827: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8136b140)
Location: fs/fs_parser.c:143
Inline: False
```
**Symbols:**

```
ffffffff8136b140-ffffffff8136b287: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813b9e00)
Location: fs/fs_parser.c:143
Inline: False
```
**Symbols:**

```
ffffffff813b9e00-ffffffff813b9f42: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8143f910)
Location: fs/fs_parser.c:143
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff8143f910-ffffffff8143fa75: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, unsigned int flags, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff814ce640)
Location: fs/fs_parser.c:144
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff814ce640-ffffffff814ce7ab: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, unsigned int flags, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81504890)
Location: fs/fs_parser.c:144
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff81504890-ffffffff81504a06: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, unsigned int flags, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81539550)
Location: fs/fs_parser.c:144
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_parse_param
```
**Symbols:**

```
ffffffff81539550-ffffffff815396c6: fs_lookup_param (STB_GLOBAL)
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
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffff8000103d6120)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffff8000103d6120-ffff8000103d628c: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05b0134)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
c05b0134-c05b0290: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c0000000004d99e0)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
c0000000004d99e0-c0000000004d9bfc: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffe00028feba)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffe00028feba-ffffffe00028ffde: fs_lookup_param (STB_GLOBAL)
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
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813164d0)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffff813164d0-ffffffff81316610: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813070c0)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffff813070c0-ffffffff81307200: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813142c0)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffff813142c0-ffffffff81314400: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fs_lookup_param(struct fs_context *fc, struct fs_parameter *param, bool want_bdev, struct path *_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81325b10)
Location: fs/fs_parser.c:253
Inline: False
```
**Symbols:**

```
ffffffff81325b10-ffffffff81325c50: fs_lookup_param (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, param, want_bdev, _path</code> ➡️ <code>fc, param, want_bdev, flags, _path</code>
</li>
</ul>
</details>
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
