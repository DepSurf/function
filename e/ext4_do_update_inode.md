# Function: <code>ext4_do_update_inode</code>

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
In fs/ext4/inode.c (ffffffff8129b084)
Location: fs/ext4/inode.c:4458
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c73b0)
Location: fs/ext4/inode.c:4784
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff812c73b0-ffffffff812c7af7: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dcf10)
Location: fs/ext4/inode.c:4926
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff812dcf10-ffffffff812dd65d: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fece0)
Location: fs/ext4/inode.c:5034
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff812fece0-ffffffff812ff44d: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81323490)
Location: fs/ext4/inode.c:5091
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81323490-ffffffff81323bfd: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81351a00)
Location: fs/ext4/inode.c:5179
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81351a00-ffffffff8135218e: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813694c0)
Location: fs/ext4/inode.c:5226
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813694c0-ffffffff81369c5a: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813928e0)
Location: fs/ext4/inode.c:5240
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813928e0-ffffffff813930ba: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ab270)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813ab270-ffffffff813aba11: ext4_do_update_inode (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff813f75e0)
Location: fs/ext4/inode.c:4963
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813f75e0-ffffffff813f7d5e: ext4_do_update_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff8140a630)
Location: fs/ext4/inode.c:5024
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff8140a630-ffffffff8140ae12: ext4_do_update_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81410800)
Location: fs/ext4/inode.c:5019
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81410800-ffffffff81410fd2: ext4_do_update_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4951
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81463530-ffffffff81463dde: ext4_do_update_inode.isra.0 (STB_LOCAL)
ffffffff81ccaa62-ffffffff81ccaa87: ext4_do_update_inode.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e2ed0)
Location: fs/ext4/inode.c:5116
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff814e2ed0-ffffffff814e32b7: ext4_do_update_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157c370)
Location: fs/ext4/inode.c:5217
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff8157c370-ffffffff8157c763: ext4_do_update_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b3770)
Location: fs/ext4/inode.c:5029
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff815b3770-ffffffff815b3b66: ext4_do_update_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ec580)
Location: fs/ext4/inode.c:5051
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff815ec580-ffffffff815ec976: ext4_do_update_inode.isra.0 (STB_LOCAL)
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
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047faf0)
Location: fs/ext4/inode.c:5248
Inline: False
```
**Symbols:**

```
ffff80001047faf0-ffff800010480278: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0640e7c)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
c0640e7c-c064163c: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a38f0)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
c0000000005a38f0-c0000000005a4250: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000308968)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffe000308968-ffffffe000309016: ext4_do_update_inode (STB_LOCAL)
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
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3850)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813a3850-ffffffff813a3ff1: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813942e0)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813942e0-ffffffff81394a81: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a10b0)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813a10b0-ffffffff813a1851: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_do_update_inode(handle_t *handle, struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b5cc0)
Location: fs/ext4/inode.c:5248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff813b5cc0-ffffffff813b6464: ext4_do_update_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
