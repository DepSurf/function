# Function: <code>ext4_ext_try_to_merge_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c4764)
Location: fs/ext4/extents.c:1802
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f3fb4)
Location: fs/ext4/extents.c:1814
Inline: True
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
In fs/ext4/extents.c (ffffffff81309f64)
Location: fs/ext4/extents.c:1814
Inline: True
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
In fs/ext4/extents.c (ffffffff812e8630)
Location: fs/ext4/extents.c:1814
Inline: True
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
In fs/ext4/extents.c (ffffffff8130d0d0)
Location: fs/ext4/extents.c:1814
Inline: True
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
In fs/ext4/extents.c (ffffffff8133c2c4)
Location: fs/ext4/extents.c:1808
Inline: True
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
In fs/ext4/extents.c (ffffffff81353974)
Location: fs/ext4/extents.c:1808
Inline: True
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
In fs/ext4/extents.c (ffffffff8137d4b4)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff81395bd4)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff813ddb74)
Location: fs/ext4/extents.c:1793
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
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
In fs/ext4/extents.c (ffffffff813ef464)
Location: fs/ext4/extents.c:1792
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
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
In fs/ext4/extents.c (ffffffff813f5924)
Location: fs/ext4/extents.c:1795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
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
In fs/ext4/extents.c (ffffffff81447674)
Location: fs/ext4/extents.c:1833
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_ext_try_to_merge_up(handle_t *handle, struct inode *inode, struct ext4_ext_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3550)
Location: fs/ext4/extents.c:1834
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff814c3550-ffffffff814c3686: ext4_ext_try_to_merge_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_ext_try_to_merge_up(handle_t *handle, struct inode *inode, struct ext4_ext_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155be50)
Location: fs/ext4/extents.c:1842
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff8155be50-ffffffff8155bf86: ext4_ext_try_to_merge_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_ext_try_to_merge_up(handle_t *handle, struct inode *inode, struct ext4_ext_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81593c60)
Location: fs/ext4/extents.c:1842
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff81593c60-ffffffff81593d96: ext4_ext_try_to_merge_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_ext_try_to_merge_up(handle_t *handle, struct inode *inode, struct ext4_ext_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cc950)
Location: fs/ext4/extents.c:1842
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff815cc950-ffffffff815cca86: ext4_ext_try_to_merge_up (STB_LOCAL)
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
In fs/ext4/extents.c (ffff800010468a08)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (c0629794)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (c000000000586fcc)
Location: fs/ext4/extents.c:1825
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_try_to_merge
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
In fs/ext4/extents.c (ffffffe0002f6566)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff8138e1b4)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff8137ec44)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff8138bb14)
Location: fs/ext4/extents.c:1825
Inline: True
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
In fs/ext4/extents.c (ffffffff8139f864)
Location: fs/ext4/extents.c:1825
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
