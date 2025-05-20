# Function: <code>dax_iomap_iter</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
loff_t dax_iomap_iter(const struct iomap_iter *iomi, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1166
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
```
**Symbols:**

```
ffffffff813f47c0-ffffffff813f4a91: dax_iomap_iter (STB_LOCAL)
ffffffff81cc600b-ffffffff81cc603f: dax_iomap_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
loff_t dax_iomap_iter(const struct iomap_iter *iomi, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1128
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
```
**Symbols:**

```
ffffffff81467e00-ffffffff81468183: dax_iomap_iter (STB_LOCAL)
ffffffff81e7821c-ffffffff81e78281: dax_iomap_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
loff_t dax_iomap_iter(const struct iomap_iter *iomi, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1400
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
```
**Symbols:**

```
ffffffff814f80d0-ffffffff814f84d1: dax_iomap_iter (STB_LOCAL)
ffffffff8206a128-ffffffff8206a16e: dax_iomap_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
loff_t dax_iomap_iter(const struct iomap_iter *iomi, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1433
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
```
**Symbols:**

```
ffffffff8152f6d0-ffffffff8152fd81: dax_iomap_iter (STB_LOCAL)
ffffffff820ea101-ffffffff820ea153: dax_iomap_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
loff_t dax_iomap_iter(const struct iomap_iter *iomi, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1419
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_rw
```
**Symbols:**

```
ffffffff815645b0-ffffffff81564c61: dax_iomap_iter (STB_LOCAL)
ffffffff821c6ba6-ffffffff821c6bf8: dax_iomap_iter.cold (STB_LOCAL)
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
