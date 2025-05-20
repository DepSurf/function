# Function: <code>ima_post_create_tmpfile</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149c840)
Location: security/integrity/ima/ima_main.c:436
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff8149c840-ffffffff8149c87f: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814b69c0)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff814b69c0-ffffffff814b69ff: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff815161a0)
Location: security/integrity/ima/ima_main.c:555
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff815161a0-ffffffff815161e3: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81533280)
Location: security/integrity/ima/ima_main.c:601
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff81533280-ffffffff815332c3: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153b770)
Location: security/integrity/ima/ima_main.c:603
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff8153b770-ffffffff8153b7c7: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8159a1f0)
Location: security/integrity/ima/ima_main.c:620
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff8159a1f0-ffffffff8159a247: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163eeb0)
Location: security/integrity/ima/ima_main.c:643
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff8163eeb0-ffffffff8163ef22: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6b80)
Location: security/integrity/ima/ima_main.c:653
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff816f6b80-ffffffff816f6bf2: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct mnt_idmap *idmap, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81730e00)
Location: security/integrity/ima/ima_main.c:672
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff81730e00-ffffffff81730e72: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct mnt_idmap *idmap, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771880)
Location: security/integrity/ima/ima_main.c:686
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff81771880-ffffffff817718f2: ima_post_create_tmpfile (STB_GLOBAL)
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
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105aec30)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffff8000105aec30-ffff8000105aecac: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e350)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
c075e350-c075e3a8: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072dce0)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
c00000000072dce0-c00000000072dd7c: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6c6c)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffe0003f6c6c-ffffffe0003f6cc2: ima_post_create_tmpfile (STB_GLOBAL)
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
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814aefa0)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff814aefa0-ffffffff814aefdf: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149f9c0)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff8149f9c0-ffffffff8149f9ff: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814ab040)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff814ab040-ffffffff814ab07f: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ima_post_create_tmpfile(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814c3a80)
Location: security/integrity/ima/ima_main.c:456
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
```
**Symbols:**

```
ffffffff814c3a80-ffffffff814c3abf: ima_post_create_tmpfile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>inode</code> ➡️ <code>mnt_userns, inode</code>
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
