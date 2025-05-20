# Function: <code>ecryptfs_lookup_interpose</code>

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
In fs/ecryptfs/inode.c (ffffffff81301cee)
Location: fs/ecryptfs/inode.c:330
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff81335d51)
Location: fs/ecryptfs/inode.c:327
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff8134ba11)
Location: fs/ecryptfs/inode.c:327
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff813605a1)
Location: fs/ecryptfs/inode.c:327
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff81385271)
Location: fs/ecryptfs/inode.c:326
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff813b407b)
Location: fs/ecryptfs/inode.c:325
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff813cd59b)
Location: fs/ecryptfs/inode.c:325
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff813f813e)
Location: fs/ecryptfs/inode.c:311
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff81411f9e)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup_interpose(struct dentry *dentry, struct dentry *lower_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:319
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8145fdb0-ffffffff8145ff17: ecryptfs_lookup_interpose (STB_LOCAL)
ffffffff814613ec-ffffffff8146142f: ecryptfs_lookup_interpose.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup_interpose(struct dentry *dentry, struct dentry *lower_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:319
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8147b9d0-ffffffff8147bb37: ecryptfs_lookup_interpose (STB_LOCAL)
ffffffff81bee059-ffffffff81bee09c: ecryptfs_lookup_interpose.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81481321)
Location: fs/ecryptfs/inode.c:317
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff814d8c21)
Location: fs/ecryptfs/inode.c:317
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8156649e)
Location: fs/ecryptfs/inode.c:317
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8160998e)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8164184e)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167ae6e)
Location: fs/ecryptfs/inode.c:327
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffff8000104f3350)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (c06b0ab8)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (c0000000006333ec)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffe0003628d4)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff8140a57e)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff813faffe)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff814078fe)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
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
In fs/ecryptfs/inode.c (ffffffff8141d5be)
Location: fs/ecryptfs/inode.c:319
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
