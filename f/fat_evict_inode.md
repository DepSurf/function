# Function: <code>fat_evict_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fc2b0)
Location: fs/fat/inode.c:556
Inline: False
```
**Symbols:**

```
ffffffff812fc2b0-ffffffff812fc305: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8132fe60)
Location: fs/fat/inode.c:637
Inline: False
```
**Symbols:**

```
ffffffff8132fe60-ffffffff8132ff22: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81345bc0)
Location: fs/fat/inode.c:637
Inline: False
```
**Symbols:**

```
ffffffff81345bc0-ffffffff81345c82: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135a660)
Location: fs/fat/inode.c:637
Inline: False
```
**Symbols:**

```
ffffffff8135a660-ffffffff8135a71e: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137f370)
Location: fs/fat/inode.c:637
Inline: False
```
**Symbols:**

```
ffffffff8137f370-ffffffff8137f42e: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:648
Inline: False
```
**Symbols:**

```
ffffffff813af3a0-ffffffff813af449: fat_evict_inode (STB_LOCAL)
ffffffff813b0086-ffffffff813b00a2: fat_evict_inode.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:644
Inline: False
```
**Symbols:**

```
ffffffff813c8840-ffffffff813c88e9: fat_evict_inode (STB_LOCAL)
ffffffff813c94ee-ffffffff813c950a: fat_evict_inode.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:645
Inline: False
```
**Symbols:**

```
ffffffff813f33d0-ffffffff813f3481: fat_evict_inode (STB_LOCAL)
ffffffff813f4091-ffffffff813f40ae: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff8140d2b0-ffffffff8140d361: fat_evict_inode (STB_LOCAL)
ffffffff8140df63-ffffffff8140df80: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff8145afe0-ffffffff8145b093: fat_evict_inode (STB_LOCAL)
ffffffff8145bd42-ffffffff8145bd5f: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff81477330-ffffffff814773e3: fat_evict_inode (STB_LOCAL)
ffffffff81bedc89-ffffffff81bedca6: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff8147cda0-ffffffff8147ce53: fat_evict_inode (STB_LOCAL)
ffffffff81bdfd93-ffffffff81bdfdb0: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:651
Inline: False
```
**Symbols:**

```
ffffffff814d44c0-ffffffff814d4573: fat_evict_inode (STB_LOCAL)
ffffffff81cd0348-ffffffff81cd0365: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:653
Inline: False
```
**Symbols:**

```
ffffffff81560540-ffffffff815605fd: fat_evict_inode (STB_LOCAL)
ffffffff81e83335-ffffffff81e83351: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81602a30)
Location: fs/fat/inode.c:648
Inline: False
```
**Symbols:**

```
ffffffff81602a30-ffffffff81602b04: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163a950)
Location: fs/fat/inode.c:648
Inline: False
```
**Symbols:**

```
ffffffff8163a950-ffffffff8163aa24: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81673e80)
Location: fs/fat/inode.c:653
Inline: False
```
**Symbols:**

```
ffffffff81673e80-ffffffff81673f54: fat_evict_inode (STB_LOCAL)
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
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104edf80)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffff8000104edf80-ffff8000104ee04c: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06aa348)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
c06aa348-c06aa434: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062cda0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
c00000000062cda0-c00000000062ceb0: fat_evict_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035e3fe)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffe00035e3fe-ffffffe00035e4c6: fat_evict_inode (STB_LOCAL)
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
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff81405890-ffffffff81405941: fat_evict_inode (STB_LOCAL)
ffffffff81406543-ffffffff81406560: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff813f6310-ffffffff813f63c1: fat_evict_inode (STB_LOCAL)
ffffffff813f6fc3-ffffffff813f6fe0: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff81402c10-ffffffff81402cc1: fat_evict_inode (STB_LOCAL)
ffffffff814038c3-ffffffff814038e0: fat_evict_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fat_evict_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:650
Inline: False
```
**Symbols:**

```
ffffffff81417080-ffffffff81417131: fat_evict_inode (STB_LOCAL)
ffffffff814191f0-ffffffff8141920d: fat_evict_inode.cold (STB_LOCAL)
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
