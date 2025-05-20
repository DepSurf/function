# Function: <code>ext4_es_scan_clu</code>

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
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135a970)
Location: fs/ext4/extents_status.c:401
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8135a970-ffffffff8135a9b5: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813839b0)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff813839b0-ffffffff813839f5: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139c440)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff8139c440-ffffffff8139c49b: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e7bd0)
Location: fs/ext4/extents_status.c:401
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813e7bd0-ffffffff813e7c9a: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9e70)
Location: fs/ext4/extents_status.c:407
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813f9e70-ffffffff813f9f57: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400230)
Location: fs/ext4/extents_status.c:407
Inline: False
```
**Symbols:**

```
ffffffff81400230-ffffffff81400317: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81452850)
Location: fs/ext4/extents_status.c:407
Inline: False
```
**Symbols:**

```
ffffffff81452850-ffffffff81452937: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cfbf0)
Location: fs/ext4/extents_status.c:407
Inline: False
```
**Symbols:**

```
ffffffff814cfbf0-ffffffff814cfd19: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81568510)
Location: fs/ext4/extents_status.c:405
Inline: False
```
**Symbols:**

```
ffffffff81568510-ffffffff81568639: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a0080)
Location: fs/ext4/extents_status.c:405
Inline: False
```
**Symbols:**

```
ffffffff815a0080-ffffffff815a0181: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8d30)
Location: fs/ext4/extents_status.c:406
Inline: False
```
**Symbols:**

```
ffffffff815d8d30-ffffffff815d8e31: ext4_es_scan_clu (STB_GLOBAL)
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
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046f1d8)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffff80001046f1d8-ffff80001046f2a8: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c06307f8)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
c06307f8-c063087c: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058f5e0)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
c00000000058f5e0-c00000000058f684: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fbeb8)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffe0002fbeb8-ffffffe0002fbf20: ext4_es_scan_clu (STB_GLOBAL)
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
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81394a20)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff81394a20-ffffffff81394a7b: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813854b0)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff813854b0-ffffffff8138550b: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81392380)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff81392380-ffffffff813923db: ext4_es_scan_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ext4_es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6290)
Location: fs/ext4/extents_status.c:401
Inline: False
```
**Symbols:**

```
ffffffff813a6290-ffffffff813a62f2: ext4_es_scan_clu (STB_GLOBAL)
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
