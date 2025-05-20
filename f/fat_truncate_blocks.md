# Function: <code>fat_truncate_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff812fa780)
Location: fs/fat/file.c:288
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff812fa780-ffffffff812faafc: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8132e590)
Location: fs/fat/file.c:349
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8132e590-ffffffff8132e8c7: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813442c0)
Location: fs/fat/file.c:349
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813442c0-ffffffff8134461c: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81358d80)
Location: fs/fat/file.c:349
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81358d80-ffffffff81359098: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8137da90)
Location: fs/fat/file.c:349
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8137da90-ffffffff8137dda8: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:349
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813acfb2-ffffffff813acff0: fat_truncate_blocks.cold.10 (STB_LOCAL)
ffffffff813ac4f0-ffffffff813ac81d: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:382
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813c6362-ffffffff813c639e: fat_truncate_blocks.cold.11 (STB_LOCAL)
ffffffff813c57b0-ffffffff813c5a99: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813f0f42-ffffffff813f0f7f: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff813f02e0-ffffffff813f05eb: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8140ae22-ffffffff8140ae5f: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff8140a1c0-ffffffff8140a4cb: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81458470)
Location: fs/fat/file.c:378
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
Direct callers:
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff81458a10-ffffffff81458a64: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff814747b0)
Location: fs/fat/file.c:378
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
Direct callers:
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff81474d90-ffffffff81474de4: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8147a164)
Location: fs/fat/file.c:378
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
Direct callers:
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff8147a810-ffffffff8147a860: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:378
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff81ccfe9c-ffffffff81ccfebb: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff814d1440-ffffffff814d14a3: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:378
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff81e830f8-ffffffff81e83117: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff8155e070-ffffffff8155e0dd: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:379
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff8207222a-ffffffff82072249: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff81600170-ffffffff816001dd: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:379
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff820f1e4d-ffffffff820f1e6c: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff81638150-ffffffff816381bd: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:379
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
```
**Symbols:**

```
ffffffff821cf12f-ffffffff821cf14e: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff81671640-ffffffff816716ad: fat_truncate_blocks (STB_GLOBAL)
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
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffff8000104ea618)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffff8000104ea618-ffff8000104ea918: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (c06a85a8)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_write_failed
```
**Symbols:**

```
c06a85a8-c06a88ec: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (c0000000006286f0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_write_failed
```
**Symbols:**

```
c0000000006286f0-c000000000628b28: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffe00035b440)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_write_failed
```
**Symbols:**

```
ffffffe00035b440-ffffffe00035b6e8: fat_truncate_blocks (STB_GLOBAL)
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
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81403402-ffffffff8140343f: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff814027a0-ffffffff81402aab: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813f3e82-ffffffff813f3ebf: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff813f3220-ffffffff813f352b: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81400782-ffffffff814007bf: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff813ffb20-ffffffff813ffe2b: fat_truncate_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fat_truncate_blocks(struct inode *inode, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:389
Inline: False
Direct callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff814163b2-ffffffff814163ef: fat_truncate_blocks.cold (STB_LOCAL)
ffffffff81415750-ffffffff81415a5b: fat_truncate_blocks (STB_GLOBAL)
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
