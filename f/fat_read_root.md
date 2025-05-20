# Function: <code>fat_read_root</code>

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
In fs/fat/inode.c (ffffffff812fd6ad)
Location: fs/fat/inode.c:1272
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8133124b)
Location: fs/fat/inode.c:1362
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81346fdd)
Location: fs/fat/inode.c:1372
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8135ba53)
Location: fs/fat/inode.c:1372
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81380756)
Location: fs/fat/inode.c:1372
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813aed3d)
Location: fs/fat/inode.c:1394
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813c7f1c)
Location: fs/fat/inode.c:1386
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813f2b05)
Location: fs/fat/inode.c:1381
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8140cac6)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_read_root(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8145a110)
Location: fs/fat/inode.c:1383
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8145a110-ffffffff8145a2e2: fat_read_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_read_root(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81476460)
Location: fs/fat/inode.c:1382
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81476460-ffffffff81476632: fat_read_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_read_root(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147bed0)
Location: fs/fat/inode.c:1382
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff8147bed0-ffffffff8147c0a2: fat_read_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fat_read_root(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814d3520)
Location: fs/fat/inode.c:1383
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff814d3520-ffffffff814d3689: fat_read_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fat_read_root(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81560930)
Location: fs/fat/inode.c:1387
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffffffff81560930-ffffffff81560a9b: fat_read_root (STB_LOCAL)
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
In fs/fat/inode.c (ffffffff816035a9)
Location: fs/fat/inode.c:1382
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff8163b4c9)
Location: fs/fat/inode.c:1382
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81674a28)
Location: fs/fat/inode.c:1390
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffff8000104ed720)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (c06ab490)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (c00000000062c54c)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffe00035dcc4)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff814050a6)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff813f5b26)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff81402426)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
In fs/fat/inode.c (ffffffff814183f6)
Location: fs/fat/inode.c:1383
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
