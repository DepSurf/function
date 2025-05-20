# Function: <code>fat_fill_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fdbc0)
Location: fs/fat/inode.c:453
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff812fdbc0-ffffffff812fdf9e: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81331b50)
Location: fs/fat/inode.c:502
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81331b50-ffffffff81331f90: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813478f0)
Location: fs/fat/inode.c:502
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813478f0-ffffffff81347d30: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135c320)
Location: fs/fat/inode.c:502
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8135c320-ffffffff8135c740: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81381020)
Location: fs/fat/inode.c:502
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81381020-ffffffff81381440: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:509
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813b00ec-ffffffff813b0122: fat_fill_inode.cold.33 (STB_LOCAL)
ffffffff813af7c0-ffffffff813afc07: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:509
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813c9554-ffffffff813c958a: fat_fill_inode.cold.37 (STB_LOCAL)
ffffffff813c8c70-ffffffff813c9073: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:510
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813f40fb-ffffffff813f4131: fat_fill_inode.cold (STB_LOCAL)
ffffffff813f37e0-ffffffff813f3bde: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8140dfcd-ffffffff8140e003: fat_fill_inode.cold (STB_LOCAL)
ffffffff8140d6c0-ffffffff8140dabe: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8145bdaa-ffffffff8145bde0: fat_fill_inode.cold (STB_LOCAL)
ffffffff8145b430-ffffffff8145b87c: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81bedcf1-ffffffff81bedd27: fat_fill_inode.cold (STB_LOCAL)
ffffffff81477780-ffffffff81477bcc: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81bdfdfb-ffffffff81bdfe31: fat_fill_inode.cold (STB_LOCAL)
ffffffff8147d200-ffffffff8147d63b: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:516
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81cd048b-ffffffff81cd04c1: fat_fill_inode.cold (STB_LOCAL)
ffffffff814d4980-ffffffff814d4d86: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:517
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81e836aa-ffffffff81e836d8: fat_fill_inode.cold (STB_LOCAL)
ffffffff81561920-ffffffff81561d58: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81604050)
Location: fs/fat/inode.c:512
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81604050-ffffffff81604488: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163bf70)
Location: fs/fat/inode.c:512
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8163bf70-ffffffff8163c3a5: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff816754d0)
Location: fs/fat/inode.c:512
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff816754d0-ffffffff81675940: fat_fill_inode (STB_GLOBAL)
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
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ee4a0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffff8000104ee4a0-ffff8000104ee8c4: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06ac080)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
c06ac080-c06ac4fc: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062d450)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
c00000000062d450-c00000000062d9ec: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035e806)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffe00035e806-ffffffe00035ebb6: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff814065ad-ffffffff814065e3: fat_fill_inode.cold (STB_LOCAL)
ffffffff81405ca0-ffffffff8140609e: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813f702d-ffffffff813f7063: fat_fill_inode.cold (STB_LOCAL)
ffffffff813f6720-ffffffff813f6b1e: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8140392d-ffffffff81403963: fat_fill_inode.cold (STB_LOCAL)
ffffffff81403020-ffffffff8140341e: fat_fill_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_fill_inode(struct inode *inode, struct msdos_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:515
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8141959d-ffffffff814195d3: fat_fill_inode.cold (STB_LOCAL)
ffffffff81418c90-ffffffff8141908e: fat_fill_inode (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
