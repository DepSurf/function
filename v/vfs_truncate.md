# Function: <code>vfs_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int vfs_truncate(struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209880)
Location: fs/open.c:72
Inline: False
Direct callers:
  - fs/open.c:do_sys_truncate
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff81209880-ffffffff81209a10: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f680)
Location: fs/open.c:72
Inline: False
Direct callers:
  - fs/open.c:do_sys_truncate
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff8122f680-ffffffff8122f823: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241bd0)
Location: fs/open.c:72
Inline: False
Direct callers:
  - fs/open.c:do_sys_truncate
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff81241bd0-ffffffff81241dcd: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d1f0)
Location: fs/open.c:72
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff8124d1f0-ffffffff8124d3e3: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126f160)
Location: fs/open.c:72
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff8126f160-ffffffff8126f361: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812954b0)
Location: fs/open.c:72
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812954b0-ffffffff812956c4: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aa3a0)
Location: fs/open.c:72
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812aa3a0-ffffffff812aa55f: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c6b70)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812c6b70-ffffffff812c6d29: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8580)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812d8580-ffffffff812d8739: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e610)
Location: fs/open.c:70
Inline: False
```
**Symbols:**

```
ffffffff8130e610-ffffffff8130e7c2: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a7c0)
Location: fs/open.c:70
Inline: False
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8131a7c0-ffffffff8131a97d: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81320c60)
Location: fs/open.c:69
Inline: False
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff81320c60-ffffffff81320dc7: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136de70)
Location: fs/open.c:70
Inline: False
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8136de70-ffffffff8136dfd7: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ec880)
Location: fs/open.c:70
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:do_sys_truncate
```
**Symbols:**

```
ffffffff813ec880-ffffffff813ec9f4: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474dc0)
Location: fs/open.c:70
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:do_sys_truncate
```
**Symbols:**

```
ffffffff81474dc0-ffffffff81474f38: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a9750)
Location: fs/open.c:71
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:do_sys_truncate
```
**Symbols:**

```
ffffffff814a9750-ffffffff814a98c4: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da7b0)
Location: fs/open.c:71
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - fs/open.c:__x64_sys_truncate
```
**Symbols:**

```
ffffffff814da7b0-ffffffff814da924: vfs_truncate (STB_GLOBAL)
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
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037d748)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffff80001037d748-ffff80001037d960: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568260)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
c0568260-c0568494: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473090)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
c000000000473090-c000000000473304: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002530c4)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffe0002530c4-ffffffe00025323a: vfs_truncate (STB_GLOBAL)
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
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d0b60)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812d0b60-ffffffff812d0d19: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c17e0)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812c17e0-ffffffff812c1999: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce970)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812ce970-ffffffff812ceb29: vfs_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfs_truncate(const struct path *path, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812df780)
Location: fs/open.c:73
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_revoke
```
**Symbols:**

```
ffffffff812df780-ffffffff812df939: vfs_truncate (STB_GLOBAL)
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
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
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
