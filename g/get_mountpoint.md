# Function: <code>get_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267890)
Location: fs/namespace.c:724
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81267890-ffffffff812679a9: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274f50)
Location: fs/namespace.c:725
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81274f50-ffffffff8127505b: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297810)
Location: fs/namespace.c:785
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81297810-ffffffff8129791b: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812beb60)
Location: fs/namespace.c:795
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812beb60-ffffffff812bec6a: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3e20)
Location: fs/namespace.c:704
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812d3e20-ffffffff812d3f52: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0e10)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812f0e10-ffffffff812f0f4c: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813029b0)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff813029b0-ffffffff81302aec: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c200)
Location: fs/namespace.c:717
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8133c200-ffffffff8133c33c: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813480a0)
Location: fs/namespace.c:717
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff813480a0-ffffffff813481dc: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134e620)
Location: fs/namespace.c:731
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8134e620-ffffffff8134e75c: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:733
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8139c630-ffffffff8139c781: get_mountpoint (STB_LOCAL)
ffffffff81cc3f49-ffffffff81cc3f65: get_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:776
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8141dc40-ffffffff8141dde5: get_mountpoint (STB_LOCAL)
ffffffff81e76820-ffffffff81e7683c: get_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:887
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff814aa560-ffffffff814aa705: get_mountpoint (STB_LOCAL)
ffffffff82068c36-ffffffff82068c52: get_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:796
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff814df520-ffffffff814df6c5: get_mountpoint (STB_LOCAL)
ffffffff820e8574-ffffffff820e8590: get_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:784
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81512280-ffffffff81512454: get_mountpoint (STB_LOCAL)
ffffffff821c52ce-ffffffff821c52ea: get_mountpoint.cold (STB_LOCAL)
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
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5ac0)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffff8000103b5ac0-ffff8000103b5cb0: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593084)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
c0593084-c0593204: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b1e00)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
c0000000004b1e00-c0000000004b203c: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002789be)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffe0002789be-ffffffe000278b6e: get_mountpoint (STB_LOCAL)
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
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812faf90)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812faf90-ffffffff812fb0cc: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ebbb0)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812ebbb0-ffffffff812ebcec: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8d80)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff812f8d80-ffffffff812f8ebc: get_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mountpoint *get_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309640)
Location: fs/namespace.c:701
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81309640-ffffffff813097ab: get_mountpoint (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
