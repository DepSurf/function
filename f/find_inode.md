# Function: <code>find_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227240)
Location: fs/inode.c:772
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff81227240-ffffffff812272f9: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f970)
Location: fs/inode.c:781
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff8124f970-ffffffff8124fa1a: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812629a0)
Location: fs/inode.c:783
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff812629a0-ffffffff81262a4a: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270230)
Location: fs/inode.c:784
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff81270230-ffffffff812702de: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292b70)
Location: fs/inode.c:784
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
```
**Symbols:**

```
ffffffff81292b70-ffffffff81292c20: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812b9b30)
Location: fs/inode.c:789
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812b9b30-ffffffff812b9be0: find_inode.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812cf000)
Location: fs/inode.c:789
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812cf000-ffffffff812cf0c9: find_inode.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812ebf30)
Location: fs/inode.c:802
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812ebf30-ffffffff812ebffb: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812fda80)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812fda80-ffffffff812fdb4b: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336460)
Location: fs/inode.c:814
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81336460-ffffffff8133652b: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341dc0)
Location: fs/inode.c:813
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81341dc0-ffffffff81341e8b: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813481b0)
Location: fs/inode.c:820
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff813481b0-ffffffff8134827b: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395dc0)
Location: fs/inode.c:824
Inline: False
Direct callers:
  - fs/inode.c:ilookup5
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81395dc0-ffffffff81395e8b: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416620)
Location: fs/inode.c:905
Inline: False
Direct callers:
  - fs/inode.c:ilookup5
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81416620-ffffffff814166e5: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1a30)
Location: fs/inode.c:904
Inline: False
Direct callers:
  - fs/inode.c:ilookup5
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff814a1a30-ffffffff814a1af5: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6b80)
Location: fs/inode.c:906
Inline: False
Direct callers:
  - fs/inode.c:ilookup5
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff814d6b80-ffffffff814d6c45: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509020)
Location: fs/inode.c:891
Inline: False
Direct callers:
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81509020-ffffffff815090e5: find_inode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffff8000103ad590)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffff8000103ad590-ffff8000103ad6e4: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *find_inode(struct super_block *sb, struct hlist_head *head, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058cd28)
Location: fs/inode.c:813
Inline: False
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
c058cd28-c058ce28: find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (c0000000004a7bb0)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
c0000000004a7bb0-c0000000004a7d68: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffe000272fa0)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffe000272fa0-ffffffe0002730c0: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812f6060)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812f6060-ffffffff812f612b: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812e6c80)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812e6c80-ffffffff812e6d4b: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812f3e70)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff812f3e70-ffffffff812f3f3b: find_inode.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff81304500)
Location: fs/inode.c:813
Inline: True
Direct callers:
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:inode_insert5
```
**Symbols:**

```
ffffffff81304500-ffffffff813045c7: find_inode.isra.0 (STB_LOCAL)
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
</ul>
