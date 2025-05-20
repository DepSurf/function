# Function: <code>reconnect_one</code>

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
In fs/exportfs/expfs.c (ffffffff8130c94b)
Location: fs/exportfs/expfs.c:119
Inline: True
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
In fs/exportfs/expfs.c (ffffffff81340cce)
Location: fs/exportfs/expfs.c:119
Inline: True
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
In fs/exportfs/expfs.c (ffffffff81356a6e)
Location: fs/exportfs/expfs.c:119
Inline: True
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
In fs/exportfs/expfs.c (ffffffff8136b580)
Location: fs/exportfs/expfs.c:120
Inline: True
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
In fs/exportfs/expfs.c (ffffffff81390110)
Location: fs/exportfs/expfs.c:120
Inline: True
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
In fs/exportfs/expfs.c (ffffffff813bf27c)
Location: fs/exportfs/expfs.c:120
Inline: True
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
In fs/exportfs/expfs.c (ffffffff813d88dc)
Location: fs/exportfs/expfs.c:120
Inline: True
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
In fs/exportfs/expfs.c (ffffffff814032c0)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (ffffffff8141d1d0)
Location: fs/exportfs/expfs.c:121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8146bca0)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff8146bca0-ffffffff8146be4b: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814863f0)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff814863f0-ffffffff8148659b: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8148bd40)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff8148bd40-ffffffff8148beea: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814e3550)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff814e3550-ffffffff814e36fa: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81571a20)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff81571a20-ffffffff81571bd2: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81616d60)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff81616d60-ffffffff81616fe6: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8164ee60)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff8164ee60-ffffffff8164f0db: reconnect_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *reconnect_one(struct vfsmount *mnt, struct dentry *dentry, char *nbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff816883a0)
Location: fs/exportfs/expfs.c:121
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
ffffffff816883a0-ffffffff8168861b: reconnect_one (STB_LOCAL)
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
In fs/exportfs/expfs.c (ffff8000104feef4)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (c06bbeb0)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (c000000000641f70)
Location: fs/exportfs/expfs.c:121
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
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
In fs/exportfs/expfs.c (ffffffe00036cc92)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (ffffffff814157b0)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (ffffffff81406230)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (ffffffff81412b30)
Location: fs/exportfs/expfs.c:121
Inline: True
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
In fs/exportfs/expfs.c (ffffffff814287b0)
Location: fs/exportfs/expfs.c:121
Inline: True
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
