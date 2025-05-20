# Function: <code>__es_find_extent_range</code>

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
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359d90)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81359d90-ffffffff81359eaa: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81382e00-ffffffff81382efa: __es_find_extent_range (STB_LOCAL)
ffffffff813848b5-ffffffff813848e7: __es_find_extent_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139b300)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff8139b300-ffffffff8139b40c: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e6ee0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff813e6ee0-ffffffff813e6fec: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f91a0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff813f91a0-ffffffff813f92ac: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813feb70)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff813feb70-ffffffff813fec7c: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81451440)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81451440-ffffffff8145154c: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cebc0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff814cebc0-ffffffff814cecd9: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81567440)
Location: fs/ext4/extents_status.c:254
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81567440-ffffffff81567559: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159f610)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff8159f610-ffffffff8159f741: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d8160)
Location: fs/ext4/extents_status.c:257
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:__revise_pending
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff815d8160-ffffffff815d827d: __es_find_extent_range (STB_LOCAL)
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
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046df18)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffff80001046df18-ffff80001046e040: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062f4bc)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
c062f4bc-c062f600: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058de90)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
c00000000058de90-c00000000058e064: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fafe8)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffe0002fafe8-ffffffe0002fb0ae: __es_find_extent_range (STB_LOCAL)
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
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813938e0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff813938e0-ffffffff813939ec: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384370)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81384370-ffffffff8138447c: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81391240)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff81391240-ffffffff8139134c: __es_find_extent_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __es_find_extent_range(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a50d0)
Location: fs/ext4/extents_status.c:256
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
**Symbols:**

```
ffffffff813a50d0-ffffffff813a51dc: __es_find_extent_range (STB_LOCAL)
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
