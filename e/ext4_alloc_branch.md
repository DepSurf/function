# Function: <code>ext4_alloc_branch</code>

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
In fs/ext4/indirect.c (ffffffff812d9138)
Location: fs/ext4/indirect.c:322
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff81308ef8)
Location: fs/ext4/indirect.c:322
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff8131ef08)
Location: fs/ext4/indirect.c:322
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff812f7b81)
Location: fs/ext4/indirect.c:322
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff8131c1c1)
Location: fs/ext4/indirect.c:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff8134a189)
Location: fs/ext4/indirect.c:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff8136234f)
Location: fs/ext4/indirect.c:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138a6a0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8138a6a0-ffffffff8138a9cf: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a30f0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813a30f0-ffffffff813a341f: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ef2c0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813ef2c0-ffffffff813ef608: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81401a10)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81401a10-ffffffff81401d58: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81407f50)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81407f50-ffffffff81408292: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145a860)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8145a860-ffffffff8145accb: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d85c0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff814d85c0-ffffffff814d8a3f: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815713a0)
Location: fs/ext4/indirect.c:328
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff815713a0-ffffffff8157182b: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a9110)
Location: fs/ext4/indirect.c:328
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff815a9110-ffffffff815a95a9: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e1d10)
Location: fs/ext4/indirect.c:328
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff815e1d10-ffffffff815e21b8: ext4_alloc_branch (STB_LOCAL)
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
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff8000104769b0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffff8000104769b0-ffff800010476d14: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c06384bc)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
c06384bc-c0638838: ext4_alloc_branch (STB_LOCAL)
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
In fs/ext4/indirect.c (c000000000599c4c)
Location: fs/ext4/indirect.c:321
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffe000302ae0)
Location: fs/ext4/indirect.c:321
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139b6d0)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8139b6d0-ffffffff8139b9ff: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138c160)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8138c160-ffffffff8138c48f: ext4_alloc_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_alloc_branch(handle_t *handle, struct ext4_allocation_request *ar, int indirect_blks, ext4_lblk_t *offsets, Indirect *branch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81398f30)
Location: fs/ext4/indirect.c:321
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81398f30-ffffffff8139925f: ext4_alloc_branch (STB_LOCAL)
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
In fs/ext4/indirect.c (ffffffff813ae0ff)
Location: fs/ext4/indirect.c:321
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
</ul>
