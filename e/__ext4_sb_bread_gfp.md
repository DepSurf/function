# Function: <code>__ext4_sb_bread_gfp</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81444f20)
Location: fs/ext4/super.c:213
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff81444f20-ffffffff81444fa7: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a840)
Location: fs/ext4/super.c:213
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff8144a840-ffffffff8144a8c8: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e300)
Location: fs/ext4/super.c:210
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff8149e300-ffffffff8149e380: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff815248f0)
Location: fs/ext4/super.c:229
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff815248f0-ffffffff81524983: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1d60)
Location: fs/ext4/super.c:222
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff815c1d60-ffffffff815c1df8: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff815f94e0)
Location: fs/ext4/super.c:222
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff815f94e0-ffffffff815f9578: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81632070)
Location: fs/ext4/super.c:223
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_sb_bread
```
**Symbols:**

```
ffffffff81632070-ffffffff81632108: __ext4_sb_bread_gfp.isra.0 (STB_LOCAL)
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
