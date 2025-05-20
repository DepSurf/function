# Function: <code>ext4_es_free_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812dac20)
Location: fs/ext4/extents_status.c:356
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
```
**Symbols:**

```
ffffffff812dac20-ffffffff812dad54: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130a6a0)
Location: fs/ext4/extents_status.c:356
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8130a6a0-ffffffff8130a7ce: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813206a0)
Location: fs/ext4/extents_status.c:356
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813206a0-ffffffff813207ce: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812ef660)
Location: fs/ext4/extents_status.c:356
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff812ef660-ffffffff812ef76f: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81314160)
Location: fs/ext4/extents_status.c:357
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81314160-ffffffff8131426f: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81342000)
Location: fs/ext4/extents_status.c:356
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81342000-ffffffff8134210d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359900)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81359900-ffffffff81359a0d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81382960)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81382960-ffffffff81382a6d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139ae60)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8139ae60-ffffffff8139af6d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e6350)
Location: fs/ext4/extents_status.c:472
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813e6350-ffffffff813e645d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f8680)
Location: fs/ext4/extents_status.c:481
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813f8680-ffffffff813f878d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813ff1c0)
Location: fs/ext4/extents_status.c:481
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813ff1c0-ffffffff813ff2cd: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814517d0)
Location: fs/ext4/extents_status.c:481
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff814517d0-ffffffff814518dd: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814cdd40)
Location: fs/ext4/extents_status.c:481
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff814cdd40-ffffffff814cde59: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815664d0)
Location: fs/ext4/extents_status.c:479
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff815664d0-ffffffff815665e9: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159e160)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8159e160-ffffffff8159e279: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d6cf0)
Location: fs/ext4/extents_status.c:510
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff815d6cf0-ffffffff815d6e09: ext4_es_free_extent (STB_LOCAL)
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
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046d8e0)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffff80001046d8e0-ffff80001046da28: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062ed28)
Location: fs/ext4/extents_status.c:472
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
c062ed28-c062ee84: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058d850)
Location: fs/ext4/extents_status.c:472
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
c00000000058d850-c00000000058d9d8: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fab70)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffe0002fab70-ffffffe0002fac94: ext4_es_free_extent (STB_LOCAL)
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
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393440)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81393440-ffffffff8139354d: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383ed0)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81383ed0-ffffffff81383fdd: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81390da0)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81390da0-ffffffff81390ead: ext4_es_free_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_es_free_extent(struct inode *inode, struct extent_status *es);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a4c30)
Location: fs/ext4/extents_status.c:472
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813a4c30-ffffffff813a4d3b: ext4_es_free_extent (STB_LOCAL)
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
