# Function: <code>__es_scan_clu</code>

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
bool __es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359f30)
Location: fs/ext4/extents_status.c:385
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_scan_clu
```
**Symbols:**

```
ffffffff81359f30-ffffffff81359f58: __es_scan_clu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __es_scan_clu(struct inode *inode, int (*matching_fn)(struct extent_status *), ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81382f80)
Location: fs/ext4/extents_status.c:385
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_scan_clu
```
**Symbols:**

```
ffffffff81382f80-ffffffff81382fac: __es_scan_clu (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff8139c463)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff813e7c08)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff813f9ee4)
Location: fs/ext4/extents_status.c:391
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff814002a4)
Location: fs/ext4/extents_status.c:391
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff814528c4)
Location: fs/ext4/extents_status.c:391
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff814cfc76)
Location: fs/ext4/extents_status.c:391
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff81568596)
Location: fs/ext4/extents_status.c:389
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff815a0106)
Location: fs/ext4/extents_status.c:389
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff815d8db6)
Location: fs/ext4/extents_status.c:390
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffff80001046f238)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (c0630824)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (c00000000058f624)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffe0002fbee2)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff81394a43)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff813854d3)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff813923a3)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
In fs/ext4/extents_status.c (ffffffff813a62b7)
Location: fs/ext4/extents_status.c:385
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan_clu
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
</ul>
