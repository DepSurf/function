# Function: <code>ext4_put_io_end_defer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129fb00)
Location: fs/ext4/page-io.c:277
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff8129fb00-ffffffff8129fbf4: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812ce3c0)
Location: fs/ext4/page-io.c:262
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff812ce3c0-ffffffff812ce4aa: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e41b0)
Location: fs/ext4/page-io.c:262
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff812e41b0-ffffffff812e429a: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131ddf0)
Location: fs/ext4/page-io.c:261
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff8131ddf0-ffffffff8131ded9: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81342400)
Location: fs/ext4/page-io.c:262
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81342400-ffffffff813424e7: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81370290)
Location: fs/ext4/page-io.c:262
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81370290-ffffffff81370377: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81388720)
Location: fs/ext4/page-io.c:262
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81388720-ffffffff81388807: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813b281a)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813b3117-ffffffff813b313d: ext4_put_io_end_defer.cold (STB_LOCAL)
ffffffff813b2800-ffffffff813b28ef: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813cb850)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813cb850-ffffffff813cb944: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81417a70)
Location: fs/ext4/page-io.c:290
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81417a70-ffffffff81417aa1: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142b570)
Location: fs/ext4/page-io.c:287
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff8142b570-ffffffff8142b5a1: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814320c0)
Location: fs/ext4/page-io.c:287
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff814320c0-ffffffff814321c2: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81485930)
Location: fs/ext4/page-io.c:287
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81485930-ffffffff81485a32: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81508de0)
Location: fs/ext4/page-io.c:289
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81508de0-ffffffff81508f6c: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a3960)
Location: fs/ext4/page-io.c:289
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff815a3960-ffffffff815a3aec: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815da3f0)
Location: fs/ext4/page-io.c:289
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff815da3f0-ffffffff815da57c: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81612bb0)
Location: fs/ext4/page-io.c:289
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff81612bb0-ffffffff81612d3c: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a3548)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffff8000104a3548-ffff8000104a367c: ext4_put_io_end_defer.part.0 (STB_LOCAL)
ffff8000104a3960-ffff8000104a39bc: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0665790)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
c0665790-c06658ac: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0000000005d08a0)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
c0000000005d08a0-c0000000005d09f8: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (ffffffe000324e52)
Location: fs/ext4/page-io.c:254
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffe000324d60-ffffffe000324e1a: ext4_put_io_end_defer.part.0 (STB_LOCAL)
ffffffe00032516c-ffffffe0003251a8: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c3e30)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813c3e30-ffffffff813c3f24: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813b48b0)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813b48b0-ffffffff813b49a4: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c12c0)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813c12c0-ffffffff813c13b4: ext4_put_io_end_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_put_io_end_defer(ext4_io_end_t *io_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813d6420)
Location: fs/ext4/page-io.c:254
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
```
**Symbols:**

```
ffffffff813d6420-ffffffff813d6514: ext4_put_io_end_defer (STB_GLOBAL)
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
