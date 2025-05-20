# Function: <code>__lookup_constant</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8130b347)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff8130aeb0-ffffffff8130af1a: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8131e338)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff8131de80-ffffffff8131deea: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81357fb5)
Location: fs/fs_parser.c:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81364a13)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff8136b463)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff813ba133)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff8143fc93)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff814ce9f3)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff81504c53)
Location: fs/fs_parser.c:27
Inline: True
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
In fs/fs_parser.c (ffffffff81539913)
Location: fs/fs_parser.c:27
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffff8000103d65e0)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffff8000103d60a0-ffff8000103d6120: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05affa4)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
c05afc7c-c05afcdc: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c0000000004da320)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
c0000000004d9790-c0000000004d99d8: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffe00029028c)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffe00028fe48-ffffffe00028feba: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81316918)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81316460-ffffffff813164ca: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81307508)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81307050-ffffffff813070ba: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81314708)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81314250-ffffffff813142ba: __lookup_constant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __lookup_constant(const struct constant_table *tbl, size_t tbl_size, const char *name, int not_found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81325f58)
Location: fs/fs_parser.c:32
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81325aa0-ffffffff81325b0a: __lookup_constant (STB_GLOBAL)
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
