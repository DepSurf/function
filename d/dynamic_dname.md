# Function: <code>dynamic_dname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81226260)
Location: fs/dcache.c:3105
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81226260-ffffffff81226312: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124e900)
Location: fs/dcache.c:3272
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff8124e900-ffffffff8124e9b3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261910)
Location: fs/dcache.c:3282
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81261910-ffffffff812619c3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126f190)
Location: fs/dcache.c:3312
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff8126f190-ffffffff8126f25d: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291ab0)
Location: fs/dcache.c:3324
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81291ab0-ffffffff81291b7d: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/d_path.c (0)
Location: fs/d_path.c:291
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff812d4314-ffffffff812d4320: dynamic_dname.cold.6 (STB_LOCAL)
ffffffff812d41a0-ffffffff812d425d: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/d_path.c (0)
Location: fs/d_path.c:291
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff812e96e4-ffffffff812e96f0: dynamic_dname.cold.6 (STB_LOCAL)
ffffffff812e9570-ffffffff812e962d: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81307e00)
Location: fs/d_path.c:291
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81307e00-ffffffff81307f33: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8131aea0)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff8131aea0-ffffffff8131afd3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81354ba0)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81354ba0-ffffffff81354cd3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813614c0)
Location: fs/d_path.c:297
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff813614c0-ffffffff813615f3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81367fa0)
Location: fs/d_path.c:297
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81367fa0-ffffffff813680d8: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6bf0)
Location: fs/d_path.c:302
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff813b6bf0-ffffffff813b6d28: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143c220)
Location: fs/d_path.c:300
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff8143c220-ffffffff8143c37a: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *dynamic_dname(char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814ca8c0)
Location: fs/d_path.c:300
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff814ca8c0-ffffffff814caa1c: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *dynamic_dname(char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81500b00)
Location: fs/d_path.c:301
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81500b00-ffffffff81500c5c: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *dynamic_dname(char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81535720)
Location: fs/d_path.c:301
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81535720-ffffffff8153587c: dynamic_dname (STB_GLOBAL)
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
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffff8000103d2200)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffff8000103d2200-ffff8000103d22cc: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05acc04)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
c05acc04-c05accac: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c0000000004d4cf0)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
c0000000004d4cf0-c0000000004d4dc4: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffe00028d486)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffe00028d486-ffffffe00028d50a: dynamic_dname (STB_GLOBAL)
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
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81313480)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81313480-ffffffff813135b3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81304090)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81304090-ffffffff813041c3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81311270)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81311270-ffffffff813113a3: dynamic_dname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *dynamic_dname(struct dentry *dentry, char *buffer, int buflen, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81322ac0)
Location: fs/d_path.c:293
Inline: False
Direct callers:
  - fs/pipe.c:pipefs_dname
  - fs/nsfs.c:ns_dname
  - fs/anon_inodes.c:anon_inodefs_dname
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - net/socket.c:sockfs_dname
```
**Symbols:**

```
ffffffff81322ac0-ffffffff81322bf3: dynamic_dname (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, buffer, buflen, fmt, (anon)</code> ➡️ <code>buffer, buflen, fmt, (anon)</code>
</li>
</ul>
</details>
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
