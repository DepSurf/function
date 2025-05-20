# Function: <code>security_path_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int security_path_rename(struct path *old_dir, struct dentry *old_dentry, struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c730)
Location: security/security.c:464
Inline: True
Direct callers:
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
```
**Symbols:**

```
ffffffff8133c730-ffffffff8133c7f8: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371d70)
Location: security/security.c:465
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff81371d70-ffffffff81371e3b: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813886a0)
Location: security/security.c:474
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff813886a0-ffffffff8138876b: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d000)
Location: security/security.c:1079
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff8139d000-ffffffff8139d0cb: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2880)
Location: security/security.c:1028
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff813c2880-ffffffff813c2957: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2950)
Location: security/security.c:570
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff813f2950-ffffffff813f2a06: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140ddf0)
Location: security/security.c:1091
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8140ddf0-ffffffff8140dea6: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bcd0)
Location: security/security.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8143bcd0-ffffffff8143bd8f: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814559f0)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff814559f0-ffffffff81455aa0: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8220)
Location: security/security.c:1293
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff814a8220-ffffffff814a82d0: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c57a0)
Location: security/security.c:1295
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff814c57a0-ffffffff814c5856: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbb70)
Location: security/security.c:1345
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff814cbb70-ffffffff814cbc26: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524990)
Location: security/security.c:1348
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff81524990-ffffffff81524a46: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8a20)
Location: security/security.c:1365
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff815b8a20-ffffffff815b8ad4: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664090)
Location: security/security.c:1363
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff81664090-ffffffff81664144: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c4d0)
Location: security/security.c:1933
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8169c4d0-ffffffff8169c584: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9170)
Location: security/security.c:2006
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff816d9170-ffffffff816d9224: security_path_rename (STB_GLOBAL)
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
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540fa0)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffff800010540fa0-ffff800010541080: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6fdc)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
c06f6fdc-c06f70bc: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006932f0)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
c0000000006932f0-c000000000693474: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ddf6)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffe00039ddf6-ffffffe00039de98: security_path_rename (STB_GLOBAL)
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
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dfd0)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8144dfd0-ffffffff8144e080: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ea20)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8143ea20-ffffffff8143ead0: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a070)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff8144a070-ffffffff8144a120: security_path_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_rename(const struct path *old_dir, struct dentry *old_dentry, const struct path *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461440)
Location: security/security.c:1145
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
```
**Symbols:**

```
ffffffff81461440-ffffffff814614f0: security_path_rename (STB_GLOBAL)
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
<code>struct path *old_dir</code> ➡️ <code>const struct path *old_dir</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path *new_dir</code> ➡️ <code>const struct path *new_dir</code>
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
