# Function: <code>security_sb_kern_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d250)
Location: security/security.c:290
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff8133d250-ffffffff8133d2ab: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372880)
Location: security/security.c:291
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff81372880-ffffffff813728db: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813891b0)
Location: security/security.c:291
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff813891b0-ffffffff8138920b: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e550)
Location: security/security.c:868
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff8139e550-ffffffff8139e5ab: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3f20)
Location: security/security.c:816
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff813c3f20-ffffffff813c3f81: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f44c0)
Location: security/security.c:384
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff813f44c0-ffffffff813f450e: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f850)
Location: security/security.c:877
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff8140f850-ffffffff8140f88a: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cde0)
Location: security/security.c:886
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8143cde0-ffffffff8143ce21: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814568b0)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff814568b0-ffffffff814568ea: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a96c0)
Location: security/security.c:1068
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount_fc
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814a96c0-ffffffff814a96fa: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6cc0)
Location: security/security.c:1070
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount_fc
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814c6cc0-ffffffff814c6cfa: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cce80)
Location: security/security.c:1115
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814cce80-ffffffff814cceba: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526000)
Location: security/security.c:1115
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81526000-ffffffff8152603a: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba3b0)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff815ba3b0-ffffffff815ba3fd: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665cf0)
Location: security/security.c:1125
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81665cf0-ffffffff81665d3d: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e2e0)
Location: security/security.c:1457
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8169e2e0-ffffffff8169e32d: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sb_kern_mount(const struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dac30)
Location: security/security.c:1510
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:vfs_cmd_create
```
**Symbols:**

```
ffffffff816dac30-ffffffff816dac7d: security_sb_kern_mount (STB_GLOBAL)
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
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542200)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff800010542200-ffff800010542250: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f81b4)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c06f81b4-c06f8208: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000695260)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c000000000695260-c000000000695308: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ebfe)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00039ebfe-ffffffe00039ec3a: security_sb_kern_mount (STB_GLOBAL)
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
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ee90)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8144ee90-ffffffff8144eeca: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f8e0)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8143f8e0-ffffffff8143f91a: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144af30)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8144af30-ffffffff8144af6a: security_sb_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sb_kern_mount(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462300)
Location: security/security.c:920
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81462300-ffffffff8146233a: security_sb_kern_mount (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct super_block *sb</code> ➡️ <code>const struct super_block *sb</code>
</li>
</ul>
</details>
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
