# Function: <code>iomap_dio_bio_iter</code>

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
loff_t iomap_dio_bio_iter(const struct iomap_iter *iter, struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:229
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81415550-ffffffff814159e9: iomap_dio_bio_iter (STB_LOCAL)
ffffffff81cc7a46-ffffffff81cc7a95: iomap_dio_bio_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_bio_iter(const struct iomap_iter *iter, struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:238
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8148ccb0-ffffffff8148d18f: iomap_dio_bio_iter (STB_LOCAL)
ffffffff81e7a613-ffffffff81e7a67f: iomap_dio_bio_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_bio_iter(const struct iomap_iter *iter, struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:238
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff815201e0-ffffffff815206d6: iomap_dio_bio_iter (STB_LOCAL)
ffffffff8206b5e4-ffffffff8206b628: iomap_dio_bio_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_bio_iter(const struct iomap_iter *iter, struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:225
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81558250-ffffffff815586fb: iomap_dio_bio_iter (STB_LOCAL)
ffffffff820eb550-ffffffff820eb594: iomap_dio_bio_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_bio_iter(const struct iomap_iter *iter, struct iomap_dio *dio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:275
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8158e880-ffffffff8158edf3: iomap_dio_bio_iter (STB_LOCAL)
ffffffff821c8797-ffffffff821c87db: iomap_dio_bio_iter.cold (STB_LOCAL)
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
