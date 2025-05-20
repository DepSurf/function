# Function: <code>pde_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f6d0)
Location: fs/proc/generic.c:540
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
```
**Symbols:**

```
ffffffff8127f6d0-ffffffff8127f70f: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac710)
Location: fs/proc/generic.c:545
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff812ac710-ffffffff812ac74f: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c2000)
Location: fs/proc/generic.c:547
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff812c2000-ffffffff812c203f: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf2c0)
Location: fs/proc/generic.c:531
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff812cf2c0-ffffffff812cf30d: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3a30)
Location: fs/proc/generic.c:541
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff812f3a30-ffffffff812f3a7e: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320ae0)
Location: fs/proc/generic.c:641
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81320ae0-ffffffff81320b1c: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337be0)
Location: fs/proc/generic.c:643
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81337be0-ffffffff81337c1c: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fd50)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff8135fd50-ffffffff8135fd8c: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377fb0)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81377fb0-ffffffff81377fec: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0f30)
Location: fs/proc/generic.c:657
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff813c0f30-ffffffff813c0fce: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2e20)
Location: fs/proc/generic.c:677
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff813d2e20-ffffffff813d2ebe: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9cb0)
Location: fs/proc/generic.c:672
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff813d9cb0-ffffffff813d9d4e: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b3e0)
Location: fs/proc/generic.c:672
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff8142b3e0-ffffffff8142b47e: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4ac0)
Location: fs/proc/generic.c:675
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
```
**Symbols:**

```
ffffffff814a4ac0-ffffffff814a4b76: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539fe0)
Location: fs/proc/generic.c:675
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
```
**Symbols:**

```
ffffffff81539fe0-ffffffff8153a096: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572280)
Location: fs/proc/generic.c:674
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
```
**Symbols:**

```
ffffffff81572280-ffffffff81572336: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aac30)
Location: fs/proc/generic.c:674
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_free_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
```
**Symbols:**

```
ffffffff815aac30-ffffffff815aace6: pde_put (STB_GLOBAL)
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
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443f10)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffff800010443f10-ffff800010443f70: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0609094)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
c0609094-c06090dc: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000559640)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
c000000000559640-c0000000005596c0: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9efc)
Location: fs/proc/generic.c:644
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffe0002d9cd6-ffffffe0002d9d18: pde_put.part.0 (STB_LOCAL)
ffffffe0002da932-ffffffe0002da978: pde_put (STB_GLOBAL)
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
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370590)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81370590-ffffffff813705cc: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81361020)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81361020-ffffffff8136105c: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136e060)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff8136e060-ffffffff8136e09c: pde_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pde_put(struct proc_dir_entry *pde);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381990)
Location: fs/proc/generic.c:644
Inline: True
Direct callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
**Symbols:**

```
ffffffff81381990-ffffffff813819cc: pde_put (STB_GLOBAL)
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
