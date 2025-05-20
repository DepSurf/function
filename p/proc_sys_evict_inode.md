# Function: <code>proc_sys_evict_inode</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d5650)
Location: fs/proc/proc_sysctl.c:506
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff812d5650-ffffffff812d56b4: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f9e90)
Location: fs/proc/proc_sysctl.c:507
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff812f9e90-ffffffff812f9ef4: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813270b0)
Location: fs/proc/proc_sysctl.c:507
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813270b0-ffffffff81327116: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133e280)
Location: fs/proc/proc_sysctl.c:505
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff8133e280-ffffffff8133e2e6: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813665a0)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813665a0-ffffffff81366614: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137e830)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff8137e830-ffffffff8137e8a4: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c8bf0)
Location: fs/proc/proc_sysctl.c:482
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813c8bf0-ffffffff813c8c64: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813dabe0)
Location: fs/proc/proc_sysctl.c:483
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813dabe0-ffffffff813dac54: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e1800)
Location: fs/proc/proc_sysctl.c:478
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813e1800-ffffffff813e1874: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433310)
Location: fs/proc/proc_sysctl.c:478
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff81433310-ffffffff81433384: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ad230)
Location: fs/proc/proc_sysctl.c:503
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff814ad230-ffffffff814ad2ad: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815436a0)
Location: fs/proc/proc_sysctl.c:496
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff815436a0-ffffffff8154371d: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157bb00)
Location: fs/proc/proc_sysctl.c:490
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff8157bb00-ffffffff8157bb7e: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b43b0)
Location: fs/proc/proc_sysctl.c:492
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff815b43b0-ffffffff815b442e: proc_sys_evict_inode (STB_GLOBAL)
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
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044ba28)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffff80001044ba28-ffff80001044bb10: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0610654)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
c0610654-c06106f8: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000563150)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
c000000000563150-c000000000563270: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e0d94)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffe0002e0d94-ffffffe0002e0e3a: proc_sys_evict_inode (STB_GLOBAL)
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
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81376e10)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff81376e10-ffffffff81376e84: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813678e0)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813678e0-ffffffff81367954: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813748e0)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813748e0-ffffffff81374954: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void proc_sys_evict_inode(struct inode *inode, struct ctl_table_header *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813882f0)
Location: fs/proc/proc_sysctl.c:514
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_evict_inode
```
**Symbols:**

```
ffffffff813882f0-ffffffff81388362: proc_sys_evict_inode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
