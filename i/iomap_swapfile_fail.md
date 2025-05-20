# Function: <code>iomap_swapfile_fail</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:74
Inline: False
```
**Symbols:**

```
ffffffff813c6820-ffffffff813c687b: iomap_swapfile_fail (STB_LOCAL)
ffffffff81bddbe1-ffffffff81bddc0b: iomap_swapfile_fail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:80
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
```
**Symbols:**

```
ffffffff81416b30-ffffffff81416b8b: iomap_swapfile_fail (STB_LOCAL)
ffffffff81cc7bc4-ffffffff81cc7bee: iomap_swapfile_fail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:80
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
```
**Symbols:**

```
ffffffff8148e140-ffffffff8148e19c: iomap_swapfile_fail (STB_LOCAL)
ffffffff81e7a7ba-ffffffff81e7a7ee: iomap_swapfile_fail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81521970)
Location: fs/iomap/swapfile.c:80
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
```
**Symbols:**

```
ffffffff81521970-ffffffff815219f4: iomap_swapfile_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff815599b0)
Location: fs/iomap/swapfile.c:80
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
```
**Symbols:**

```
ffffffff815599b0-ffffffff81559a34: iomap_swapfile_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info *isi, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff81590140)
Location: fs/iomap/swapfile.c:80
Inline: False
Direct callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
  - fs/iomap/swapfile.c:iomap_swapfile_iter
```
**Symbols:**

```
ffffffff81590140-ffffffff815901f4: iomap_swapfile_fail (STB_LOCAL)
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
