# Function: <code>ext4_trim_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d5912)
Location: fs/ext4/mballoc.c:5048
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813055c4)
Location: fs/ext4/mballoc.c:5051
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8131b58b)
Location: fs/ext4/mballoc.c:5058
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312981)
Location: fs/ext4/mballoc.c:5124
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8133723e)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81365979)
Location: fs/ext4/mballoc.c:5098
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137dd39)
Location: fs/ext4/mballoc.c:5105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a4440)
Location: fs/ext4/mballoc.c:5107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bd2b0)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_trim_extent(struct super_block *sb, int start, int count, ext4_group_t group, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81408f60)
Location: fs/ext4/mballoc.c:5373
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
**Symbols:**

```
ffffffff81408f60-ffffffff8140918c: ext4_trim_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_trim_extent(struct super_block *sb, int start, int count, ext4_group_t group, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141b480)
Location: fs/ext4/mballoc.c:5660
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
**Symbols:**

```
ffffffff8141b480-ffffffff8141b676: ext4_trim_extent (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff81421b51)
Location: fs/ext4/mballoc.c:6193
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
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
In fs/ext4/mballoc.c (ffffffff81474292)
Location: fs/ext4/mballoc.c:6269
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
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
In fs/ext4/mballoc.c (ffffffff814f6382)
Location: fs/ext4/mballoc.c:6356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
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
In fs/ext4/mballoc.c (ffffffff8159073b)
Location: fs/ext4/mballoc.c:6325
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
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
In fs/ext4/mballoc.c (ffffffff815c78ee)
Location: fs/ext4/mballoc.c:6901
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
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
In fs/ext4/mballoc.c (ffffffff815ff527)
Location: fs/ext4/mballoc.c:6718
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010493fa0)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06555f0)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bcf7c)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe0003189b0)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b5890)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a6320)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b30f0)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c7c39)
Location: fs/ext4/mballoc.c:5128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
