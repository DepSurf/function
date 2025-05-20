# Function: <code>ext4_es_scan_range</code>

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
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135a920)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8135a920-ffffffff8135a96f: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383960)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81383960-ffffffff813839af: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139c3f0)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8139c3f0-ffffffff8139c43f: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e7b10)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813e7b10-ffffffff813e7bc1: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9da0)
Location: fs/ext4/extents_status.c:361
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813f9da0-ffffffff813f9e6c: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400160)
Location: fs/ext4/extents_status.c:361
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81400160-ffffffff8140022c: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81452780)
Location: fs/ext4/extents_status.c:361
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81452780-ffffffff8145284c: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cfad0)
Location: fs/ext4/extents_status.c:361
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff814cfad0-ffffffff814cfbe8: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815683e0)
Location: fs/ext4/extents_status.c:359
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815683e0-ffffffff815684f8: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159ff80)
Location: fs/ext4/extents_status.c:359
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8159ff80-ffffffff815a0070: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8c30)
Location: fs/ext4/extents_status.c:360
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815d8c30-ffffffff815d8d20: ext4_es_scan_range (STB_GLOBAL)
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
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046f108)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffff80001046f108-ffff80001046f1d4: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0630784)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c0630784-c06307f8: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058f550)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c00000000058f550-c00000000058f5d4: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fbe5c)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffe0002fbe5c-ffffffe0002fbeb8: ext4_es_scan_range (STB_GLOBAL)
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
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813949d0)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813949d0-ffffffff81394a1f: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81385460)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81385460-ffffffff813854af: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81392330)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81392330-ffffffff8139237f: ext4_es_scan_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6230)
Location: fs/ext4/extents_status.c:358
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a6230-ffffffff813a6287: ext4_es_scan_range (STB_GLOBAL)
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
