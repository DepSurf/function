# Function: <code>iov_iter_xarray</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aafe0)
Location: lib/iov_iter.c:1328
Inline: True
```
**Symbols:**

```
ffffffff815aafe0-ffffffff815ab005: iov_iter_xarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614580)
Location: lib/iov_iter.c:1190
Inline: False
```
**Symbols:**

```
ffffffff81614580-ffffffff816145aa: iov_iter_xarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1130)
Location: lib/iov_iter.c:1242
Inline: False
```
**Symbols:**

```
ffffffff816e1130-ffffffff816e116d: iov_iter_xarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d15d0)
Location: lib/iov_iter.c:1060
Inline: False
```
**Symbols:**

```
ffffffff817d15d0-ffffffff817d160d: iov_iter_xarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81810360)
Location: lib/iov_iter.c:756
Inline: False
```
**Symbols:**

```
ffffffff81810360-ffffffff8181039d: iov_iter_xarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iov_iter_xarray(struct iov_iter *i, unsigned int direction, struct xarray *xarray, loff_t start, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855e50)
Location: lib/iov_iter.c:655
Inline: False
```
**Symbols:**

```
ffffffff81855e50-ffffffff81855e8d: iov_iter_xarray (STB_GLOBAL)
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
