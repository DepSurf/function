# Function: <code>iomap_readahead</code>

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
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac820)
Location: fs/iomap/buffered-io.c:412
Inline: False
```
**Symbols:**

```
ffffffff813ac820-ffffffff813ac9c4: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813be010)
Location: fs/iomap/buffered-io.c:393
Inline: False
```
**Symbols:**

```
ffffffff813be010-ffffffff813be18b: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4760)
Location: fs/iomap/buffered-io.c:393
Inline: False
```
**Symbols:**

```
ffffffff813c4760-ffffffff813c48d0: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:400
Inline: False
```
**Symbols:**

```
ffffffff81cc7a03-ffffffff81cc7a46: iomap_readahead.cold (STB_LOCAL)
ffffffff81414c10-ffffffff81414f70: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:400
Inline: False
```
**Symbols:**

```
ffffffff81e7a585-ffffffff81e7a5ed: iomap_readahead.cold (STB_LOCAL)
ffffffff8148c320-ffffffff8148c6dd: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:405
Inline: False
```
**Symbols:**

```
ffffffff8206b39e-ffffffff8206b406: iomap_readahead.cold (STB_LOCAL)
ffffffff8151eab0-ffffffff8151edf2: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:405
Inline: False
```
**Symbols:**

```
ffffffff820eb2fa-ffffffff820eb354: iomap_readahead.cold (STB_LOCAL)
ffffffff81556c10-ffffffff81556f4d: iomap_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iomap_readahead(struct readahead_control *rac, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:485
Inline: False
```
**Symbols:**

```
ffffffff821c83f0-ffffffff821c8457: iomap_readahead.cold (STB_LOCAL)
ffffffff8158d0d0-ffffffff8158d412: iomap_readahead (STB_GLOBAL)
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
