# Function: <code>privileged_wrt_inode_uidgid</code>

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
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810926f0)
Location: kernel/capability.c:467
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810926f0-ffffffff8109272b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f830)
Location: kernel/capability.c:467
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff8108f830-ffffffff8108f86b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810966f0)
Location: kernel/capability.c:468
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810966f0-ffffffff8109672b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099c00)
Location: kernel/capability.c:468
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff81099c00-ffffffff81099c3b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1f90)
Location: kernel/capability.c:470
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810a1f90-ffffffff810a1fcb: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a69c0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810a69c0-ffffffff810a69fb: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acfa0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810acfa0-ffffffff810acfdb: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b488b)
Location: kernel/capability.c:487
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
Direct callers:
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810b4aa0-ffffffff810b4adb: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afa8b)
Location: kernel/capability.c:487
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
Direct callers:
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810afcc0-ffffffff810afcfb: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b11c0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810b11c0-ffffffff810b1219: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c3280)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810c3280-ffffffff810c32d9: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da740)
Location: kernel/capability.c:488
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810da740-ffffffff810da817: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa800)
Location: kernel/capability.c:488
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810fa800-ffffffff810fa8d7: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811068a0)
Location: kernel/capability.c:475
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff811068a0-ffffffff81106917: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811101f0)
Location: kernel/capability.c:475
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff811101f0-ffffffff81110267: privileged_wrt_inode_uidgid (STB_GLOBAL)
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
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff8000101067c0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffff8000101067c0-ffff800010106820: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c03614d0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
c03614d0-c036151c: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014db60)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
c00000000014db60-c00000000014dbf8: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb532)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffe0000cb532-ffffffe0000cb592: privileged_wrt_inode_uidgid (STB_GLOBAL)
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
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a7310)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810a7310-ffffffff810a734b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095cf0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff81095cf0-ffffffff81095d2b: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6870)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810a6870-ffffffff810a68ab: privileged_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool privileged_wrt_inode_uidgid(struct user_namespace *ns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae9a0)
Location: kernel/capability.c:487
Inline: False
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - fs/exec.c:would_dump
```
**Symbols:**

```
ffffffff810ae9a0-ffffffff810ae9db: privileged_wrt_inode_uidgid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>ns, inode</code> ➡️ <code>ns, mnt_userns, inode</code>
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
