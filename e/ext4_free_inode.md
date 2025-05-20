# Function: <code>ext4_free_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81293bd0)
Location: fs/ext4/ialloc.c:253
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81293bd0-ffffffff81294225: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c1180)
Location: fs/ext4/ialloc.c:253
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff812c1180-ffffffff812c17b8: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d67b0)
Location: fs/ext4/ialloc.c:253
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff812d67b0-ffffffff812d6dea: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f4a90)
Location: fs/ext4/ialloc.c:255
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff812f4a90-ffffffff812f50a6: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81319220)
Location: fs/ext4/ialloc.c:256
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81319220-ffffffff813197fb: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8134925b-ffffffff81349278: ext4_free_inode.cold.25 (STB_LOCAL)
ffffffff81347040-ffffffff813475ac: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8136141b-ffffffff81361438: ext4_free_inode.cold.26 (STB_LOCAL)
ffffffff8135f1f0-ffffffff8135f75c: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8138a49b-ffffffff8138a4b8: ext4_free_inode.cold (STB_LOCAL)
ffffffff813883e0-ffffffff8138890b: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813a2ee6-ffffffff813a2f03: ext4_free_inode.cold (STB_LOCAL)
ffffffff813a0da0-ffffffff813a12ba: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:233
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813ef017-ffffffff813ef034: ext4_free_inode.cold (STB_LOCAL)
ffffffff813ed010-ffffffff813ed53c: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81bec362-ffffffff81bec37f: ext4_free_inode.cold (STB_LOCAL)
ffffffff813ff1e0-ffffffff813ff71e: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81bde40d-ffffffff81bde42a: ext4_free_inode.cold (STB_LOCAL)
ffffffff81405570-ffffffff81405acd: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81cca2ca-ffffffff81cca335: ext4_free_inode.cold (STB_LOCAL)
ffffffff81457da0-ffffffff81458321: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81e7d002-ffffffff81e7d06a: ext4_free_inode.cold (STB_LOCAL)
ffffffff814d5900-ffffffff814d5eed: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8206d5ea-ffffffff8206d635: ext4_free_inode.cold (STB_LOCAL)
ffffffff8156e690-ffffffff8156ec9a: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff820ed314-ffffffff820ed33b: ext4_free_inode.cold (STB_LOCAL)
ffffffff815a6540-ffffffff815a6ad5: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:235
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff821ca45a-ffffffff821ca481: ext4_free_inode.cold (STB_LOCAL)
ffffffff815df3c0-ffffffff815df955: ext4_free_inode (STB_GLOBAL)
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
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff8000104745a0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffff8000104745a0-ffff800010474b4c: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0635af8)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c0635af8-c0636114: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c000000000595b40)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c000000000595b40-c0000000005962bc: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe000300054)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffe000300054-ffffffe00030057e: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8139b4c6-ffffffff8139b4e3: ext4_free_inode.cold (STB_LOCAL)
ffffffff81399380-ffffffff8139989a: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8138bf56-ffffffff8138bf73: ext4_free_inode.cold (STB_LOCAL)
ffffffff81389e10-ffffffff8138a32a: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81398d26-ffffffff81398d43: ext4_free_inode.cold (STB_LOCAL)
ffffffff81396be0-ffffffff813970fa: ext4_free_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ext4_free_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:231
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813ad14c-ffffffff813ad169: ext4_free_inode.cold (STB_LOCAL)
ffffffff813aaed0-ffffffff813ab41b: ext4_free_inode (STB_GLOBAL)
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
