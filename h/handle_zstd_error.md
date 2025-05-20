# Function: <code>handle_zstd_error</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff82ffa512)
Location: lib/decompress_unzstd.c:92
Inline: False
Direct callers:
  - lib/decompress_unzstd.c:decompress_single
  - lib/decompress_unzstd.c:decompress_single
```
**Symbols:**

```
ffffffff82ffa512-ffffffff82ffa576: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff8320511e)
Location: lib/decompress_unzstd.c:92
Inline: False
```
**Symbols:**

```
ffffffff8320511e-ffffffff83205182: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff832ecdf8)
Location: lib/decompress_unzstd.c:92
Inline: False
```
**Symbols:**

```
ffffffff832ecdf8-ffffffff832ece5c: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff834a4a9a)
Location: lib/decompress_unzstd.c:88
Inline: False
```
**Symbols:**

```
ffffffff834a4a9a-ffffffff834a4b23: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff83f1bba0)
Location: lib/decompress_unzstd.c:88
Inline: False
```
**Symbols:**

```
ffffffff83f1bba0-ffffffff83f1bc2d: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff83742430)
Location: lib/decompress_unzstd.c:90
Inline: False
```
**Symbols:**

```
ffffffff83742430-ffffffff837424bd: handle_zstd_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_zstd_error(size_t ret, void (*error)(char *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff83976f20)
Location: lib/decompress_unzstd.c:90
Inline: False
```
**Symbols:**

```
ffffffff83976f20-ffffffff83976fad: handle_zstd_error (STB_LOCAL)
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
