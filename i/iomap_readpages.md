# Function: <code>iomap_readpages</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81325f80)
Location: fs/iomap.c:462
Inline: False
```
**Symbols:**

```
ffffffff81325f80-ffffffff81326131: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c9f0)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff8134c9f0-ffffffff8134cb74: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364be0)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff81364be0-ffffffff81364d64: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a6d8)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffff80001042a6d8-ffff80001042a88c: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4cf8)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
c05f4cf8-c05f4f50: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053bd80)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
c00000000053bd80-c00000000053bfd0: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8be6)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffe0002c8be6-ffffffe0002c8d02: iomap_readpages (STB_GLOBAL)
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
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135d1c0)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff8135d1c0-ffffffff8135d344: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134de60)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff8134de60-ffffffff8134dfe4: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135ac90)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff8135ac90-ffffffff8135ae14: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_readpages(struct address_space *mapping, struct list_head *pages, unsigned int nr_pages, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136e410)
Location: fs/iomap/buffered-io.c:381
Inline: False
```
**Symbols:**

```
ffffffff8136e410-ffffffff8136e594: iomap_readpages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
