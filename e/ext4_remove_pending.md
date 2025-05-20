# Function: <code>ext4_remove_pending</code>

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
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b380)
Location: fs/ext4/extents_status.c:1532
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff8135b380-ffffffff8135b3b5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813843b0)
Location: fs/ext4/extents_status.c:1531
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff813843b0-ffffffff813843e5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139d030)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff8139d030-ffffffff8139d065: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e8770)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff813e8770-ffffffff813e87a5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813faa20)
Location: fs/ext4/extents_status.c:1943
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff813faa20-ffffffff813faa55: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400de0)
Location: fs/ext4/extents_status.c:1941
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff81400de0-ffffffff81400e15: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814533f0)
Location: fs/ext4/extents_status.c:1941
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff814533f0-ffffffff81453425: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814d09c0)
Location: fs/ext4/extents_status.c:1941
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff814d09c0-ffffffff814d0a05: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815693a0)
Location: fs/ext4/extents_status.c:1938
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff815693a0-ffffffff815693e5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a1050)
Location: fs/ext4/extents_status.c:1976
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff815a1050-ffffffff815a1095: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d9db0)
Location: fs/ext4/extents_status.c:2022
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff815d9db0-ffffffff815d9df5: ext4_remove_pending (STB_GLOBAL)
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
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff800010470118)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffff800010470118-ffff8000104701a0: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0631600)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
c0631600-c063164c: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c000000000590740)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
c000000000590740-c0000000005907a0: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fc990)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffe0002fc990-ffffffe0002fc9d6: ext4_remove_pending (STB_GLOBAL)
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
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81395610)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff81395610-ffffffff81395645: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813860a0)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff813860a0-ffffffff813860d5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81392f70)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff81392f70-ffffffff81392fa5: ext4_remove_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_remove_pending(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6fe0)
Location: fs/ext4/extents_status.c:1922
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
**Symbols:**

```
ffffffff813a6fe0-ffffffff813a701f: ext4_remove_pending (STB_GLOBAL)
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
