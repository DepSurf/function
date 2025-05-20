# Function: <code>read_blocklist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81322800)
Location: fs/squashfs/file.c:335
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff8133868d)
Location: fs/squashfs/file.c:335
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff8134d1f2)
Location: fs/squashfs/file.c:335
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813718a2)
Location: fs/squashfs/file.c:335
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813a026d)
Location: fs/squashfs/file.c:339
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813b8fef)
Location: fs/squashfs/file.c:339
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813e3e1a)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813fde6b)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffff8144b380)
Location: fs/squashfs/file.c:326
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8144b380-ffffffff8144b468: read_blocklist.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffff81467a60)
Location: fs/squashfs/file.c:326
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81467a60-ffffffff81467b48: read_blocklist.constprop.0 (STB_LOCAL)
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
In fs/squashfs/file.c (ffffffff8146d5b4)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff814c3e48)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff8154ea3b)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_blocklist(struct inode *inode, int index, u64 *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff815ee930)
Location: fs/squashfs/file.c:327
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff815ee930-ffffffff815eea43: read_blocklist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_blocklist(struct inode *inode, int index, u64 *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81626920)
Location: fs/squashfs/file.c:327
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff81626920-ffffffff81626a33: read_blocklist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_blocklist(struct inode *inode, int index, u64 *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8165fa90)
Location: fs/squashfs/file.c:327
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff8165fa90-ffffffff8165fba3: read_blocklist (STB_LOCAL)
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
In fs/squashfs/file.c (ffff8000104dbf24)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (c069d708)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (c000000000617230)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffe000350b50)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813f644b)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813e6ecb)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813f37cb)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff814093ef)
Location: fs/squashfs/file.c:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
