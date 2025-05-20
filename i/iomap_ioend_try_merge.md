# Function: <code>iomap_ioend_try_merge</code>

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
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends, void (*merge_private)(struct iomap_ioend *, struct iomap_ioend *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813a9c20)
Location: fs/iomap/buffered-io.c:1167
Inline: False
```
**Symbols:**

```
ffffffff813a9c20-ffffffff813a9cdb: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends, void (*merge_private)(struct iomap_ioend *, struct iomap_ioend *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb270)
Location: fs/iomap/buffered-io.c:1137
Inline: False
```
**Symbols:**

```
ffffffff813bb270-ffffffff813bb32b: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c23b0)
Location: fs/iomap/buffered-io.c:1137
Inline: False
```
**Symbols:**

```
ffffffff813c23b0-ffffffff813c2447: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81411ef0)
Location: fs/iomap/buffered-io.c:1106
Inline: False
```
**Symbols:**

```
ffffffff81411ef0-ffffffff81411f87: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81487e00)
Location: fs/iomap/buffered-io.c:1133
Inline: False
```
**Symbols:**

```
ffffffff81487e00-ffffffff81487ec7: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151ba20)
Location: fs/iomap/buffered-io.c:1394
Inline: False
```
**Symbols:**

```
ffffffff8151ba20-ffffffff8151bae7: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81553ce0)
Location: fs/iomap/buffered-io.c:1414
Inline: False
```
**Symbols:**

```
ffffffff81553ce0-ffffffff81553daa: iomap_ioend_try_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iomap_ioend_try_merge(struct iomap_ioend *ioend, struct list_head *more_ioends);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81589ca0)
Location: fs/iomap/buffered-io.c:1582
Inline: False
```
**Symbols:**

```
ffffffff81589ca0-ffffffff81589d6a: iomap_ioend_try_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*merge_private)(struct iomap_ioend *, struct iomap_ioend *)</code>
</li>
</ul>
</details>
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
