# Function: <code>proc_fd_access_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127b7a0)
Location: fs/proc/base.c:691
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_follow_link
```
**Symbols:**

```
ffffffff8127b7a0-ffffffff8127b7ef: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a82b0)
Location: fs/proc/base.c:688
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
```
**Symbols:**

```
ffffffff812a82b0-ffffffff812a8305: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bdb90)
Location: fs/proc/base.c:674
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
```
**Symbols:**

```
ffffffff812bdb90-ffffffff812bdbe5: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cb1f0)
Location: fs/proc/base.c:651
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff812cb1f0-ffffffff812cb245: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ef920)
Location: fs/proc/base.c:651
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff812ef920-ffffffff812ef975: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131c6c0)
Location: fs/proc/base.c:628
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8131c6c0-ffffffff8131c715: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81333ef0)
Location: fs/proc/base.c:648
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff81333ef0-ffffffff81333f45: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135c520)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8135c520-ffffffff8135c580: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81374980)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff81374980-ffffffff813749e0: proc_fd_access_allowed (STB_LOCAL)
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
In fs/proc/base.c (ffffffff813bddc4)
Location: fs/proc/base.c:663
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cfb14)
Location: fs/proc/base.c:672
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff813d67a3)
Location: fs/proc/base.c:669
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff81427433)
Location: fs/proc/base.c:673
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff814a1014)
Location: fs/proc/base.c:672
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
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
In fs/proc/base.c (ffffffff81536014)
Location: fs/proc/base.c:673
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
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
In fs/proc/base.c (ffffffff8156e1e4)
Location: fs/proc/base.c:674
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
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
In fs/proc/base.c (ffffffff815a6b74)
Location: fs/proc/base.c:674
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
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
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043dff8)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffff80001043dff8-ffff80001043e06c: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0604684)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
c0604684-c06046e4: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000553450)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
c000000000553450-c000000000553518: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d4d48)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffe0002d4d48-ffffffe0002d4dba: proc_fd_access_allowed (STB_LOCAL)
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
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136cf60)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8136cf60-ffffffff8136cfc0: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135d9f0)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8135d9f0-ffffffff8135da50: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136aa30)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8136aa30-ffffffff8136aa90: proc_fd_access_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_fd_access_allowed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137e440)
Location: fs/proc/base.c:661
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff8137e440-ffffffff8137e4a0: proc_fd_access_allowed (STB_LOCAL)
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
