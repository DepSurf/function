# Function: <code>ext4_getfsmap_find_sb</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff812f2a3c)
Location: fs/ext4/fsmap.c:324
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff81316fc5)
Location: fs/ext4/fsmap.c:324
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff81344d55)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8135cea5)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8138603a)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8139ea8a)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ext4_getfsmap_find_sb(struct super_block *sb, ext4_group_t agno, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813ea760)
Location: fs/ext4/fsmap.c:311
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff813ea760-ffffffff813ea923: ext4_getfsmap_find_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ext4_getfsmap_find_sb(struct super_block *sb, ext4_group_t agno, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813fca10)
Location: fs/ext4/fsmap.c:314
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff813fca10-ffffffff813fcbd3: ext4_getfsmap_find_sb (STB_LOCAL)
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
In fs/ext4/fsmap.c (ffffffff8140286d)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff81454f3d)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff814d277d)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff8156b31d)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff815a31dc)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff815dbefc)
Location: fs/ext4/fsmap.c:314
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffff800010471fe8)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (c0633044)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (c000000000592bfc)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffe0002fdfaa)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8139706a)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff81387afa)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff813949ca)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff813a8aba)
Location: fs/ext4/fsmap.c:311
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
