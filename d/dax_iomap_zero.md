# Function: <code>dax_iomap_zero</code>

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
int dax_iomap_zero(loff_t pos, unsigned int offset, unsigned int size, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138fbc0)
Location: fs/dax.c:1041
Inline: False
```
**Symbols:**

```
ffffffff8138fbc0-ffffffff8138fd01: dax_iomap_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s64 dax_iomap_zero(loff_t pos, u64 length, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a11a0)
Location: fs/dax.c:1057
Inline: False
```
**Symbols:**

```
ffffffff813a11a0-ffffffff813a136e: dax_iomap_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s64 dax_iomap_zero(loff_t pos, u64 length, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a8330)
Location: fs/dax.c:1069
Inline: False
```
**Symbols:**

```
ffffffff813a8330-ffffffff813a84fe: dax_iomap_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s64 dax_iomap_zero(loff_t pos, u64 length, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f7a70)
Location: fs/dax.c:1129
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
```
**Symbols:**

```
ffffffff813f7a70-ffffffff813f7c3e: dax_iomap_zero (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 length</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>pos, offset, size, iomap</code> ➡️ <code>pos, length, iomap</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>s64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
