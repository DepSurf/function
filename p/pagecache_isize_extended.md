# Function: <code>pagecache_isize_extended</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119e5d0)
Location: mm/truncate.c:733
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff8119e5d0-ffffffff8119e6a0: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b4180)
Location: mm/truncate.c:754
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff811b4180-ffffffff811b4275: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c47f0)
Location: mm/truncate.c:786
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff811c47f0-ffffffff811c48e5: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cd120)
Location: mm/truncate.c:805
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff811cd120-ffffffff811cd1c4: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2450)
Location: mm/truncate.c:858
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff811e2450-ffffffff811e2529: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81203560)
Location: mm/truncate.c:849
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81203560-ffffffff81203632: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812164a0)
Location: mm/truncate.c:850
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:__generic_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812164a0-ffffffff81216573: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:853
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81226da0-ffffffff81226dca: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff81225e70-ffffffff81225f57: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233cd0)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81233cd0-ffffffff81233db2: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261300)
Location: mm/truncate.c:865
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81261300-ffffffff812613e8: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b700)
Location: mm/truncate.c:893
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8126b700-ffffffff8126b7e5: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270290)
Location: mm/truncate.c:784
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81270290-ffffffff81270375: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:783
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81cba5f1-ffffffff81cba612: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff812ad520-ffffffff812ad617: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:801
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81e6be5e-ffffffff81e6be7f: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff81307fa0-ffffffff81308120: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:791
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8206279a-ffffffff820627bb: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff81371f50-ffffffff813720d0: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:791
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff820e1f40-ffffffff820e1f61: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff813a40f0-ffffffff813a4276: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:780
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff821be959-ffffffff821be97a: pagecache_isize_extended.cold (STB_LOCAL)
ffffffff813cdc40-ffffffff813cddc0: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3b40)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffff8000102c3b40-ffff8000102c3c44: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04eec04)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c04eec04-c04eed60: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037e790)
Location: mm/truncate.c:865
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c00000000037e790-c00000000037e910: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e4cda)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffe0001e4cda-ffffffe0001e4d9c: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122c320)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8122c320-ffffffff8122c402: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121f400)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8121f400-ffffffff8121f4e2: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122a0c0)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8122a0c0-ffffffff8122a1a2: pagecache_isize_extended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pagecache_isize_extended(struct inode *inode, loff_t from, loff_t to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812394b0)
Location: mm/truncate.c:865
Inline: True
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/buffer.c:generic_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812394b0-ffffffff81239592: pagecache_isize_extended (STB_GLOBAL)
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
