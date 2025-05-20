# Function: <code>ext4_ext_convert_to_initialized</code>

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
In fs/ext4/extents.c (ffffffff812c7dc3)
Location: fs/ext4/extents.c:3392
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff812f85cf)
Location: fs/ext4/extents.c:3406
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff8130e5f4)
Location: fs/ext4/extents.c:3406
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff812ebde3)
Location: fs/ext4/extents.c:3407
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff813108a5)
Location: fs/ext4/extents.c:3407
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8133e6b8)
Location: fs/ext4/extents.c:3401
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8135521e)
Location: fs/ext4/extents.c:3463
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3483
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8137e780-ffffffff8137eff2: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff8138265a-ffffffff8138268c: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81396ea0)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff81396ea0-ffffffff81397717: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e2890)
Location: fs/ext4/extents.c:3369
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813e2890-ffffffff813e30b2: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f40f0)
Location: fs/ext4/extents.c:3368
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813f40f0-ffffffff813f4904: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fa320)
Location: fs/ext4/extents.c:3374
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813fa320-ffffffff813fab37: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3412
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8144c740-ffffffff8144cf2a: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff81cc9447-ffffffff81cc94a5: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3410
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff814c90f0-ffffffff814c9953: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff81e7c156-ffffffff81e7c1b5: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff81561760-ffffffff81561fc3: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff8206c7ab-ffffffff8206c80a: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff815994f0-ffffffff81599d38: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff820ec594-ffffffff820ec5e6: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:3391
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff815d2330-ffffffff815d2b85: ext4_ext_convert_to_initialized (STB_LOCAL)
ffffffff821c97c8-ffffffff821c9830: ext4_ext_convert_to_initialized.cold (STB_LOCAL)
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
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010469bb0)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffff800010469bb0-ffff80001046a320: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062a948)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
c062a948-c062b164: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000588a60)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
c000000000588a60-c00000000058928c: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f74d4)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffe0002f74d4-ffffffe0002f7c0a: ext4_ext_convert_to_initialized (STB_LOCAL)
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
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138f480)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8138f480-ffffffff8138fcf7: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ff10)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8137ff10-ffffffff81380787: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138cde0)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff8138cde0-ffffffff8138d657: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_convert_to_initialized(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a0b30)
Location: fs/ext4/extents.c:3529
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813a0b30-ffffffff813a13ea: ext4_ext_convert_to_initialized (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
