# Function: <code>bitmap_file_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169c240)
Location: drivers/md/bitmap.c:808
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
```
**Symbols:**

```
ffffffff8169c240-ffffffff8169c2ce: bitmap_file_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fd5a0)
Location: drivers/md/bitmap.c:805
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff816fd5a0-ffffffff816fd62e: bitmap_file_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f220)
Location: drivers/md/bitmap.c:827
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff8172f220-ffffffff8172f2ae: bitmap_file_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81748840)
Location: drivers/md/bitmap.c:829
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff81748840-ffffffff817488d0: bitmap_file_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bab20)
Location: drivers/md/md-bitmap.c:833
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff817bab20-ffffffff817babb0: bitmap_file_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_file_unmap(struct bitmap_storage *store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81802bd0)
Location: drivers/md/md-bitmap.c:833
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff81802bd0-ffffffff81802c60: bitmap_file_unmap (STB_LOCAL)
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
