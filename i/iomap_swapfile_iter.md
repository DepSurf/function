# Function: <code>iomap_swapfile_iter</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t iomap_swapfile_iter(const struct iomap_iter *iter, struct iomap *iomap, struct iomap_swapfile_info *isi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81416c30)
Location: fs/iomap/swapfile.c:97
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81416c30-ffffffff81416dab: iomap_swapfile_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
loff_t iomap_swapfile_iter(const struct iomap_iter *iter, struct iomap *iomap, struct iomap_swapfile_info *isi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff8148e240)
Location: fs/iomap/swapfile.c:97
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8148e240-ffffffff8148e3dc: iomap_swapfile_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
loff_t iomap_swapfile_iter(const struct iomap_iter *iter, struct iomap *iomap, struct iomap_swapfile_info *isi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81521ac0)
Location: fs/iomap/swapfile.c:97
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81521ac0-ffffffff81521c67: iomap_swapfile_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
loff_t iomap_swapfile_iter(const struct iomap_iter *iter, struct iomap *iomap, struct iomap_swapfile_info *isi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81559b00)
Location: fs/iomap/swapfile.c:97
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81559b00-ffffffff81559ca7: iomap_swapfile_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
loff_t iomap_swapfile_iter(const struct iomap_iter *iter, struct iomap *iomap, struct iomap_swapfile_info *isi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff815902c0)
Location: fs/iomap/swapfile.c:97
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff815902c0-ffffffff81590467: iomap_swapfile_iter (STB_LOCAL)
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
