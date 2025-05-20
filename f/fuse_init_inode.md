# Function: <code>fuse_init_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131bf39)
Location: fs/fuse/inode.c:258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81350a1e)
Location: fs/fuse/inode.c:256
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8136637e)
Location: fs/fuse/inode.c:258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137aa3e)
Location: fs/fuse/inode.c:258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139f8de)
Location: fs/fuse/inode.c:258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cec7e)
Location: fs/fuse/inode.c:258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e80ee)
Location: fs/fuse/inode.c:257
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814141ae)
Location: fs/fuse/inode.c:255
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142e24e)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147de9f)
Location: fs/fuse/inode.c:247
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81497200)
Location: fs/fuse/inode.c:274
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81497200-ffffffff814972e0: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149c370)
Location: fs/fuse/inode.c:274
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8149c370-ffffffff8149c450: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f3ec0)
Location: fs/fuse/inode.c:276
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff814f3ec0-ffffffff814f3fa0: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81583880)
Location: fs/fuse/inode.c:314
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81583880-ffffffff815839a8: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr, struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81629860)
Location: fs/fuse/inode.c:314
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81629860-ffffffff8162997a: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr, struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81661a70)
Location: fs/fuse/inode.c:314
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81661a70-ffffffff81661b8a: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_init_inode(struct inode *inode, struct fuse_attr *attr, struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169b9c0)
Location: fs/fuse/inode.c:375
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8169b9c0-ffffffff8169bad4: fuse_init_inode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010512928)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cda34)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c00000000065a68c)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c970)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142682e)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814172ae)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814229ce)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814397fe)
Location: fs/fuse/inode.c:245
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>struct fuse_conn *fc</code>
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
