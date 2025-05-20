# Function: <code>security_path_mknod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_mknod(struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133bf40)
Location: security/security.c:413
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:SyS_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8133bf40-ffffffff8133bfb9: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371510)
Location: security/security.c:414
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81371510-ffffffff81371589: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387e40)
Location: security/security.c:423
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81387e40-ffffffff81387eb9: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cd70)
Location: security/security.c:1028
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8139cd70-ffffffff8139cde9: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c25b0)
Location: security/security.c:977
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:path_openat
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813c25b0-ffffffff813c262f: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2700)
Location: security/security.c:519
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813f2700-ffffffff813f276a: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dba0)
Location: security/security.c:1040
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:path_openat
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8140dba0-ffffffff8140dc0a: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ba40)
Location: security/security.c:1054
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8143ba40-ffffffff8143bab5: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814557a0)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff814557a0-ffffffff81455808: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7fd0)
Location: security/security.c:1242
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:may_o_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff814a7fd0-ffffffff814a8038: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5550)
Location: security/security.c:1244
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:may_o_create
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff814c5550-ffffffff814c55b8: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cba40)
Location: security/security.c:1297
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff814cba40-ffffffff814cbaa8: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524740)
Location: security/security.c:1297
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81524740-ffffffff815247a8: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8870)
Location: security/security.c:1317
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff815b8870-ffffffff815b8909: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663eb0)
Location: security/security.c:1315
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81663eb0-ffffffff81663f49: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c2f0)
Location: security/security.c:1824
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8169c2f0-ffffffff8169c389: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d8f90)
Location: security/security.c:1897
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff816d8f90-ffffffff816d9029: security_path_mknod (STB_GLOBAL)
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
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540cd0)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010540cd0-ffff800010540d54: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6d18)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c06f6d18-c06f6d98: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000692e20)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c000000000692e20-c000000000692ef8: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039dbe4)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe00039dbe4-ffffffe00039dc46: security_path_mknod (STB_GLOBAL)
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
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dd80)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8144dd80-ffffffff8144dde8: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e7d0)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8143e7d0-ffffffff8143e838: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449e20)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81449e20-ffffffff81449e88: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_mknod(const struct path *dir, struct dentry *dentry, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814611f0)
Location: security/security.c:1094
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:lookup_open
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff814611f0-ffffffff81461258: security_path_mknod (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *dir</code> ➡️ <code>const struct path *dir</code>
</li>
</ul>
</details>
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
