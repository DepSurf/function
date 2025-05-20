# Function: <code>bd_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81249600)
Location: fs/block_dev.c:727
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81249600-ffffffff81249690: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812720a0)
Location: fs/block_dev.c:804
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812720a0-ffffffff81272106: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81285b80)
Location: fs/block_dev.c:1056
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81285b80-ffffffff81285be6: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292ec0)
Location: fs/block_dev.c:981
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bd_acquire
```
**Symbols:**

```
ffffffff81292ec0-ffffffff81292f24: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5cb0)
Location: fs/block_dev.c:971
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bd_acquire
```
**Symbols:**

```
ffffffff812b5cb0-ffffffff812b5d14: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd910)
Location: fs/block_dev.c:972
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812dd910-ffffffff812dd974: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2ef0)
Location: fs/block_dev.c:1011
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812f2ef0-ffffffff812f2f54: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314960)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81314960-ffffffff813149c4: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327140)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81327140-ffffffff813271a4: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361142)
Location: fs/block_dev.c:989
Inline: True
Inline callers:
  - fs/block_dev.c:bd_acquire
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff813619b0-ffffffff81361a17: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1f10)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bd_acquire
```
**Symbols:**

```
ffff8000103e1f10-ffff8000103e1ff4: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba1bc)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bd_acquire
```
**Symbols:**

```
c05ba1bc-c05ba240: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7a80)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bd_acquire
```
**Symbols:**

```
c0000000004e7a80-c0000000004e7b4c: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002985be)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffe0002985be-ffffffe00029865c: bd_forget (STB_GLOBAL)
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
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f720)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff8131f720-ffffffff8131f784: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813102c0)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff813102c0-ffffffff81310324: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d1f0)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff8131d1f0-ffffffff8131d254: bd_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bd_forget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132eed0)
Location: fs/block_dev.c:1008
Inline: False
Direct callers:
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff8132eed0-ffffffff8132ef55: bd_forget (STB_GLOBAL)
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
