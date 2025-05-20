# Function: <code>proc_tid_comm_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a8500)
Location: fs/proc/base.c:3183
Inline: False
```
**Symbols:**

```
ffffffff812a8500-ffffffff812a8579: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bdde0)
Location: fs/proc/base.c:3218
Inline: False
```
**Symbols:**

```
ffffffff812bdde0-ffffffff812bde59: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812caac0)
Location: fs/proc/base.c:3344
Inline: False
```
**Symbols:**

```
ffffffff812caac0-ffffffff812cab39: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ef360)
Location: fs/proc/base.c:3344
Inline: False
```
**Symbols:**

```
ffffffff812ef360-ffffffff812ef3d9: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131c220)
Location: fs/proc/base.c:3259
Inline: False
```
**Symbols:**

```
ffffffff8131c220-ffffffff8131c29b: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81333670)
Location: fs/proc/base.c:3353
Inline: False
```
**Symbols:**

```
ffffffff81333670-ffffffff813336eb: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135b670)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff8135b670-ffffffff8135b6f2: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81373ac0)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff81373ac0-ffffffff81373b42: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bbc00)
Location: fs/proc/base.c:3461
Inline: False
```
**Symbols:**

```
ffffffff813bbc00-ffffffff813bbc9e: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cd7c0)
Location: fs/proc/base.c:3478
Inline: False
```
**Symbols:**

```
ffffffff813cd7c0-ffffffff813cd85e: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d47e0)
Location: fs/proc/base.c:3490
Inline: True
```
**Symbols:**

```
ffffffff813d47e0-ffffffff813d4885: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81426120)
Location: fs/proc/base.c:3496
Inline: True
```
**Symbols:**

```
ffffffff81426120-ffffffff814261c5: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8149f590)
Location: fs/proc/base.c:3545
Inline: True
```
**Symbols:**

```
ffffffff8149f590-ffffffff8149f64d: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81534310)
Location: fs/proc/base.c:3561
Inline: True
```
**Symbols:**

```
ffffffff81534310-ffffffff815343cd: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct mnt_idmap *idmap, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156c4d0)
Location: fs/proc/base.c:3563
Inline: True
```
**Symbols:**

```
ffffffff8156c4d0-ffffffff8156c58d: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int proc_tid_comm_permission(struct mnt_idmap *idmap, struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a4cd0)
Location: fs/proc/base.c:3570
Inline: True
```
**Symbols:**

```
ffffffff815a4cd0-ffffffff815a4d8d: proc_tid_comm_permission (STB_LOCAL)
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
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043dc90)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffff80001043dc90-ffff80001043dd3c: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c06041ec)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
c06041ec-c0604280: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000552780)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
c000000000552780-c000000000552888: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d6380)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffe0002d6380-ffffffe0002d640e: proc_tid_comm_permission (STB_LOCAL)
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
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136c0a0)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff8136c0a0-ffffffff8136c122: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135cb30)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff8135cb30-ffffffff8135cbb2: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81369b70)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff81369b70-ffffffff81369bf2: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_tid_comm_permission(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137d440)
Location: fs/proc/base.c:3385
Inline: False
```
**Symbols:**

```
ffffffff8137d440-ffffffff8137d4c2: proc_tid_comm_permission (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask</code> ➡️ <code>mnt_userns, inode, mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
