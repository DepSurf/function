# Function: <code>ext4_extent_block_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c2800)
Location: fs/ext4/extents.c:60
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff812c2800-ffffffff812c287c: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f21c0)
Location: fs/ext4/extents.c:60
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff812f21c0-ffffffff812f223c: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81308190)
Location: fs/ext4/extents.c:60
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff81308190-ffffffff8130820c: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e69a0)
Location: fs/ext4/extents.c:60
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff812e69a0-ffffffff812e6a1c: ext4_extent_block_csum (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff8130b5b9)
Location: fs/ext4/extents.c:60
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813397c6)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81350966)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813795dc)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391820)
Location: fs/ext4/extents.c:48
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff81391820-ffffffff81391895: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd616)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813eef06)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813f5397)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81447ad6)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff814c4009)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff8155c625)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81594425)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff815cd115)
Location: fs/ext4/extents.c:49
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffff8000104646f4)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (c0624970)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (c000000000581738)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffe0002f28c2)
Location: fs/ext4/extents.c:48
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389e00)
Location: fs/ext4/extents.c:48
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff81389e00-ffffffff81389e75: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a890)
Location: fs/ext4/extents.c:48
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff8137a890-ffffffff8137a905: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387760)
Location: fs/ext4/extents.c:48
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff81387760-ffffffff813877d5: ext4_extent_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__le32 ext4_extent_block_csum(struct inode *inode, struct ext4_extent_header *eh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b440)
Location: fs/ext4/extents.c:48
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff8139b440-ffffffff8139b4b5: ext4_extent_block_csum (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
