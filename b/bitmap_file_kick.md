# Function: <code>bitmap_file_kick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169d400)
Location: drivers/md/bitmap.c:840
Inline: True
Direct callers:
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff8169d400-ffffffff8169d4cf: bitmap_file_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fe6d0)
Location: drivers/md/bitmap.c:837
Inline: True
Direct callers:
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff816fe6d0-ffffffff816fe79e: bitmap_file_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81730330)
Location: drivers/md/bitmap.c:859
Inline: True
Direct callers:
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff81730330-ffffffff817303fe: bitmap_file_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817481a0)
Location: drivers/md/bitmap.c:861
Inline: True
Direct callers:
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff817481a0-ffffffff81748272: bitmap_file_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817ba430)
Location: drivers/md/md-bitmap.c:865
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817ba430-ffffffff817ba505: bitmap_file_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_file_kick(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:865
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81802410-ffffffff81802481: bitmap_file_kick (STB_LOCAL)
ffffffff81805f79-ffffffff81805fef: bitmap_file_kick.cold.30 (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
