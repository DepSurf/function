# Function: <code>free_ext_idx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff812cc4a0)
Location: fs/ext4/migrate.c:383
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff812cc4a0-ffffffff812cc58f: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff812fbde0)
Location: fs/ext4/migrate.c:383
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff812fbde0-ffffffff812fbed0: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81311d90)
Location: fs/ext4/migrate.c:383
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff81311d90-ffffffff81311e80: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81313820)
Location: fs/ext4/migrate.c:383
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff81313820-ffffffff81313923: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81337fe0)
Location: fs/ext4/migrate.c:383
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff81337fe0-ffffffff813380e3: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81366540)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff81366540-ffffffff8136664c: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff8137e9a0)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff8137e9a0-ffffffff8137ea92: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813a7e20)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813a7e20-ffffffff813a7f10: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813c0c50)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813c0c50-ffffffff813c0d40: free_ext_idx (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff8140cc50)
Location: fs/ext4/migrate.c:353
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8140cc50-ffffffff8140cda1: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff814200b0)
Location: fs/ext4/migrate.c:353
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff814200b0-ffffffff81420201: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff814268f0)
Location: fs/ext4/migrate.c:353
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff814268f0-ffffffff81426a2f: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff8147a580)
Location: fs/ext4/migrate.c:353
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8147a580-ffffffff8147a6bf: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff814fc8c0)
Location: fs/ext4/migrate.c:353
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff814fc8c0-ffffffff814fca38: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff81597030)
Location: fs/ext4/migrate.c:352
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81597030-ffffffff815971a8: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff815cda70)
Location: fs/ext4/migrate.c:352
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff815cda70-ffffffff815cdbe8: free_ext_idx.isra.0 (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff816062f0)
Location: fs/ext4/migrate.c:352
Inline: True
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff816062f0-ffffffff81606468: free_ext_idx.isra.0 (STB_LOCAL)
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
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffff800010497fb0)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffff800010497fb0-ffff8000104980e0: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (c0659a30)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
c0659a30-c0659b60: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (c0000000005c2280)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
c0000000005c2280-c0000000005c2408: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffe00031c25a)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffe00031c25a-ffffffe00031c33c: free_ext_idx (STB_LOCAL)
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
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813b9230)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813b9230-ffffffff813b9320: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813a9cc0)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813a9cc0-ffffffff813a9db0: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813b6a90)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813b6a90-ffffffff813b6b80: free_ext_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int free_ext_idx(handle_t *handle, struct inode *inode, struct ext4_extent_idx *ix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff813cb7a0)
Location: fs/ext4/migrate.c:376
Inline: False
Direct callers:
  - fs/ext4/migrate.c:free_ext_idx
```
**Symbols:**

```
ffffffff813cb7a0-ffffffff813cb890: free_ext_idx (STB_LOCAL)
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
