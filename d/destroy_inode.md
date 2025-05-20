# Function: <code>destroy_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227c40)
Location: fs/inode.c:250
Inline: True
Direct callers:
  - fs/inode.c:evict
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff81227c40-ffffffff81227c93: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250370)
Location: fs/inode.c:257
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81250370-ffffffff812503c6: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263410)
Location: fs/inode.c:259
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81263410-ffffffff81263466: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270c30)
Location: fs/inode.c:260
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81270c30-ffffffff81270c85: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293560)
Location: fs/inode.c:260
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81293560-ffffffff812935b8: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b91a0)
Location: fs/inode.c:262
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812b91a0-ffffffff812b91f9: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce2f0)
Location: fs/inode.c:262
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812ce2f0-ffffffff812ce349: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb1b0)
Location: fs/inode.c:270
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812eb1b0-ffffffff812eb223: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fccf0)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812fccf0-ffffffff812fcd63: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335590)
Location: fs/inode.c:275
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81335590-ffffffff81335603: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340f10)
Location: fs/inode.c:276
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81340f10-ffffffff81340f83: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347300)
Location: fs/inode.c:276
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81347300-ffffffff81347373: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394d60)
Location: fs/inode.c:280
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81394d60-ffffffff81394dd3: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417110)
Location: fs/inode.c:304
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81417110-ffffffff8141718f: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a2720)
Location: fs/inode.c:302
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff814a2720-ffffffff814a279f: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d7890)
Location: fs/inode.c:302
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff814d7890-ffffffff814d790f: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509ba0)
Location: fs/inode.c:303
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81509ba0-ffffffff81509c1f: destroy_inode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103acf20)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffff8000103acf20-ffff8000103acf9c: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058de68)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
c058de68-c058dedc: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a8770)
Location: fs/inode.c:274
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
c0000000004a8770-c0000000004a8828: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000271cf0)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffe000271cf0-ffffffe000271d60: destroy_inode (STB_LOCAL)
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
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f52d0)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812f52d0-ffffffff812f5343: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5ef0)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812e5ef0-ffffffff812e5f63: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f30e0)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff812f30e0-ffffffff812f3153: destroy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void destroy_inode(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304a30)
Location: fs/inode.c:274
Inline: True
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:evict
```
**Symbols:**

```
ffffffff81304a30-ffffffff81304aa3: destroy_inode (STB_LOCAL)
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
