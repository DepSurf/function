# Function: <code>proc_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81279b20)
Location: fs/proc/inode.c:416
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81279b20-ffffffff81279c87: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812a6890)
Location: fs/proc/inode.c:418
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff812a6890-ffffffff812a69f7: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812bc180)
Location: fs/proc/inode.c:431
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff812bc180-ffffffff812bc2df: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812c9560)
Location: fs/proc/inode.c:432
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff812c9560-ffffffff812c9691: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff812edde0)
Location: fs/proc/inode.c:433
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff812edde0-ffffffff812edf11: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8131ae60)
Location: fs/proc/inode.c:450
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff8131ae60-ffffffff8131af8a: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81331ee0)
Location: fs/proc/inode.c:450
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81331ee0-ffffffff8133200a: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/inode.c (0)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81359e66-ffffffff81359e7d: proc_get_inode.cold (STB_LOCAL)
ffffffff81359d30-ffffffff81359e66: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81371f80)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81371f80-ffffffff813720c0: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813ba040)
Location: fs/proc/inode.c:618
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff813ba040-ffffffff813ba1ab: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813cbae0)
Location: fs/proc/inode.c:658
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff813cbae0-ffffffff813cbca9: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813d2ad0)
Location: fs/proc/inode.c:644
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff813d2ad0-ffffffff813d2c99: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81424020)
Location: fs/proc/inode.c:644
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81424020-ffffffff814241e9: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8149cbb0)
Location: fs/proc/inode.c:644
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff8149cbb0-ffffffff8149cd8d: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff815315d0)
Location: fs/proc/inode.c:652
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff815315d0-ffffffff815317ad: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff815697a0)
Location: fs/proc/inode.c:652
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff815697a0-ffffffff8156997d: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff815a1dc0)
Location: fs/proc/inode.c:646
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff815a1dc0-ffffffff815a1f82: proc_get_inode (STB_GLOBAL)
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
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffff80001043c060)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffff80001043c060-ffff80001043c19c: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (c06022a0)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
c06022a0-c0602408: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (c00000000054fd50)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
c00000000054fd50-c00000000054ff10: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffe0002d44f4)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffe0002d44f4-ffffffe0002d45f8: proc_get_inode (STB_GLOBAL)
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
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8136a560)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff8136a560-ffffffff8136a6a0: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8135aff0)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff8135aff0-ffffffff8135b130: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81368030)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff81368030-ffffffff81368170: proc_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *proc_get_inode(struct super_block *sb, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8137b680)
Location: fs/proc/inode.c:449
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
  - fs/proc/generic.c:proc_lookup_de
```
**Symbols:**

```
ffffffff8137b680-ffffffff8137b7c0: proc_get_inode (STB_GLOBAL)
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
