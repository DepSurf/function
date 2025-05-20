# Function: <code>__fat_write_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fb8e0)
Location: fs/fat/inode.c:742
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
```
**Symbols:**

```
ffffffff812fb8e0-ffffffff812fbb47: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8132f490)
Location: fs/fat/inode.c:825
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8132f490-ffffffff8132f703: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813451f0)
Location: fs/fat/inode.c:825
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813451f0-ffffffff81345463: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81359c60)
Location: fs/fat/inode.c:825
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81359c60-ffffffff81359ebf: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137e970)
Location: fs/fat/inode.c:825
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8137e970-ffffffff8137ebcf: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:844
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813ae270-ffffffff813ae4f1: __fat_write_inode (STB_LOCAL)
ffffffff813afd98-ffffffff813afdbb: __fat_write_inode.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:840
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813c84a0-ffffffff813c86d1: __fat_write_inode (STB_LOCAL)
ffffffff813c94cb-ffffffff813c94ee: __fat_write_inode.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:835
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813f3050-ffffffff813f3270: __fat_write_inode (STB_LOCAL)
ffffffff813f406e-ffffffff813f4091: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8140cf30-ffffffff8140d150: __fat_write_inode (STB_LOCAL)
ffffffff8140df40-ffffffff8140df63: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8145ac60-ffffffff8145ae80: __fat_write_inode (STB_LOCAL)
ffffffff8145bd1f-ffffffff8145bd42: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:846
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81476fb0-ffffffff814771d0: __fat_write_inode (STB_LOCAL)
ffffffff81bedc66-ffffffff81bedc89: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:846
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8147ca20-ffffffff8147cc3d: __fat_write_inode (STB_LOCAL)
ffffffff81bdfd70-ffffffff81bdfd93: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff814d4130-ffffffff814d4356: __fat_write_inode (STB_LOCAL)
ffffffff81cd0308-ffffffff81cd0348: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:851
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff815602d0-ffffffff81560520: __fat_write_inode (STB_LOCAL)
ffffffff81e832f5-ffffffff81e83335: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:846
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81602780-ffffffff816029eb: __fat_write_inode (STB_LOCAL)
ffffffff82072269-ffffffff82072286: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:846
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff8163a6a0-ffffffff8163a90b: __fat_write_inode (STB_LOCAL)
ffffffff820f1e8c-ffffffff820f1ea9: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:851
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81673b90-ffffffff81673e31: __fat_write_inode (STB_LOCAL)
ffffffff821cf16e-ffffffff821cf18b: __fat_write_inode.cold (STB_LOCAL)
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
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ecbe0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffff8000104ecbe0-ffff8000104ece90: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06a99d4)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
c06a99d4-c06a9c5c: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c000000000629fb0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
c000000000629fb0-c00000000062a3b0: __fat_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035d32a)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffe00035d32a-ffffffe00035d58e: __fat_write_inode (STB_LOCAL)
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
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81405510-ffffffff81405730: __fat_write_inode (STB_LOCAL)
ffffffff81406520-ffffffff81406543: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff813f5f90-ffffffff813f61b0: __fat_write_inode (STB_LOCAL)
ffffffff813f6fa0-ffffffff813f6fc3: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81402890-ffffffff81402ab0: __fat_write_inode (STB_LOCAL)
ffffffff814038a0-ffffffff814038c3: __fat_write_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __fat_write_inode(struct inode *inode, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:847
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_sync_inode
  - fs/fat/inode.c:fat_evict_inode
```
**Symbols:**

```
ffffffff81416720-ffffffff81416967: __fat_write_inode (STB_LOCAL)
ffffffff81419197-ffffffff814191ba: __fat_write_inode.cold (STB_LOCAL)
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
