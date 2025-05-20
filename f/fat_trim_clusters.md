# Function: <code>fat_trim_clusters</code>

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
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813c3da0)
Location: fs/fat/fatent.c:694
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff813c3da0-ffffffff813c3dea: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ee530)
Location: fs/fat/fatent.c:694
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff813ee530-ffffffff813ee580: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81408500)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff81408500-ffffffff81408550: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff814578da)
Location: fs/fat/fatent.c:753
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81473c9a)
Location: fs/fat/fatent.c:753
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff814796e6)
Location: fs/fat/fatent.c:753
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff814d0c3b)
Location: fs/fat/fatent.c:754
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8155d7d7)
Location: fs/fat/fatent.c:755
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff815ff827)
Location: fs/fat/fatent.c:755
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81637807)
Location: fs/fat/fatent.c:755
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81670cf7)
Location: fs/fat/fatent.c:755
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e89f8)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffff8000104e89f8-ffff8000104e8a68: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a688c)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
c06a688c-c06a6924: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000626680)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
c000000000626680-c0000000006266f4: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe000359f42)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffe000359f42-ffffffe000359fae: fat_trim_clusters (STB_LOCAL)
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
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81400ae0)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff81400ae0-ffffffff81400b30: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813f1560)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff813f1560-ffffffff813f15b0: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813fde60)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff813fde60-ffffffff813fdeb0: fat_trim_clusters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_trim_clusters(struct super_block *sb, u32 clus, u32 nr_clus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81413b10)
Location: fs/fat/fatent.c:697
Inline: False
Direct callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
```
**Symbols:**

```
ffffffff81413b10-ffffffff81413b60: fat_trim_clusters (STB_LOCAL)
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
