# Function: <code>inode_sb_list_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812265a0)
Location: fs/inode.c:425
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812265a0-ffffffff81226604: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ec60)
Location: fs/inode.c:433
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff8124ec60-ffffffff8124ecc4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81261c70)
Location: fs/inode.c:435
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81261c70-ffffffff81261cd4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126f530)
Location: fs/inode.c:435
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff8126f530-ffffffff8126f594: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81291e50)
Location: fs/inode.c:435
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81291e50-ffffffff81291eb4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9200)
Location: fs/inode.c:441
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812b9200-ffffffff812b9264: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce350)
Location: fs/inode.c:441
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812ce350-ffffffff812ce3b4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb230)
Location: fs/inode.c:454
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812eb230-ffffffff812eb294: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fcd70)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812fcd70-ffffffff812fcdd4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337232)
Location: fs/inode.c:459
Inline: True
Inline callers:
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
Direct callers:
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff81335a50-ffffffff81335ab7: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342b72)
Location: fs/inode.c:460
Inline: True
Inline callers:
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
Direct callers:
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff813413d0-ffffffff81341437: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348b42)
Location: fs/inode.c:460
Inline: True
Inline callers:
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
Direct callers:
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff813477d0-ffffffff81347837: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813967dc)
Location: fs/inode.c:464
Inline: True
Inline callers:
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
Direct callers:
  - fs/inode.c:iget_locked
```
**Symbols:**

```
ffffffff813953a0-ffffffff81395407: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81418d38)
Location: fs/inode.c:492
Inline: True
Inline callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81415a10-ffffffff81415a81: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a466a)
Location: fs/inode.c:491
Inline: True
Inline callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff814a0de0-ffffffff814a0e51: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d97fa)
Location: fs/inode.c:491
Inline: True
Inline callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff814d60f0-ffffffff814d6161: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150bfa5)
Location: fs/inode.c:492
Inline: True
Inline callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff815084c0-ffffffff81508531: inode_sb_list_add (STB_GLOBAL)
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
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ad070)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffff8000103ad070-ffff8000103ad110: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058bdcc)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
c058bdcc-c058be34: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a8830)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
c0000000004a8830-c0000000004a8908: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000271d60)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffe000271d60-ffffffe000271dec: inode_sb_list_add (STB_GLOBAL)
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
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5350)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812f5350-ffffffff812f53b4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5f70)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812e5f70-ffffffff812e5fd4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3160)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff812f3160-ffffffff812f31c4: inode_sb_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inode_sb_list_add(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81302f20)
Location: fs/inode.c:458
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81302f20-ffffffff81302f82: inode_sb_list_add (STB_GLOBAL)
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
