# Function: <code>LZ4_decompress_safe</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8147a060)
Location: lib/lz4/lz4_decompress.c:337
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8147a060-ffffffff8147a493: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff814a7400)
Location: lib/lz4/lz4_decompress.c:337
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff814a7400-ffffffff814a77ab: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff814dc890)
Location: lib/lz4/lz4_decompress.c:337
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff814dc890-ffffffff814dcc26: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff814f1300)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff814f1300-ffffffff814f1747: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8151e370)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8151e370-ffffffff8151e7ac: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8153f200)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8153f200-ffffffff8153f63c: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff815a88c0)
Location: lib/lz4/lz4_decompress.c:452
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff815a88c0-ffffffff815a8cf5: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff815c43c0)
Location: lib/lz4/lz4_decompress.c:456
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff815c43c0-ffffffff815c47fb: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff815ca000)
Location: lib/lz4/lz4_decompress.c:456
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff815ca000-ffffffff815ca433: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff816344c0)
Location: lib/lz4/lz4_decompress.c:456
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff816344c0-ffffffff81634932: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81706060)
Location: lib/lz4/lz4_decompress.c:460
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81706060-ffffffff81706460: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff817f8d40)
Location: lib/lz4/lz4_decompress.c:460
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff817f8d40-ffffffff817f9140: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81839120)
Location: lib/lz4/lz4_decompress.c:460
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81839120-ffffffff818395fe: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8188ace0)
Location: lib/lz4/lz4_decompress.c:460
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8188ace0-ffffffff8188b1be: LZ4_decompress_safe (STB_GLOBAL)
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
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffff80001064b840)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffff80001064b840-ffff80001064bda0: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (c07f6f5c)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
c07f6f5c-c07f74c0: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (c0000000007f9a60)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
c0000000007f9a60-c0000000007fa020: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffe000477782)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffe000477782-ffffffe000477e2a: LZ4_decompress_safe (STB_GLOBAL)
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
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff815377e0)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff815377e0-ffffffff81537c1c: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81527ac0)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81527ac0-ffffffff81527efc: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff81533520)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff81533520-ffffffff8153395c: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int LZ4_decompress_safe(const char *source, char *dest, int compressedSize, int maxDecompressedSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_decompress.c (ffffffff8154d350)
Location: lib/lz4/lz4_decompress.c:449
Inline: False
Direct callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_usingDict
  - lib/lz4/lz4_decompress.c:LZ4_decompress_safe_continue
  - lib/decompress_unlz4.c:unlz4
```
**Symbols:**

```
ffffffff8154d350-ffffffff8154d78c: LZ4_decompress_safe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
