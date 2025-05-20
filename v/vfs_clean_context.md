# Function: <code>vfs_clean_context</code>

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
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130ad30)
Location: fs/fs_context.c:734
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8130ad30-ffffffff8130adb6: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dd10)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8131dd10-ffffffff8131dd85: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357ad0)
Location: fs/fs_context.c:665
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81357ad0-ffffffff81357b4b: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813645c0)
Location: fs/fs_context.c:665
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813645c0-ffffffff8136463b: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136b020)
Location: fs/fs_context.c:665
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8136b020-ffffffff8136b09b: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9ce0)
Location: fs/fs_context.c:683
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813b9ce0-ffffffff813b9d5b: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f7c0)
Location: fs/fs_context.c:683
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8143f7c0-ffffffff8143f845: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce4c0)
Location: fs/fs_context.c:683
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814ce4c0-ffffffff814ce545: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81504710)
Location: fs/fs_context.c:705
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81504710-ffffffff81504793: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815393d0)
Location: fs/fs_context.c:735
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff815393d0-ffffffff8153945d: vfs_clean_context (STB_GLOBAL)
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
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5ea8)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff8000103d5ea8-ffff8000103d5f20: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05afb5c)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c05afb5c-c05afbd8: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d95e0)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c0000000004d95e0-c0000000004d9694: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028fd50)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00028fd50-ffffffe00028fdc4: vfs_clean_context (STB_GLOBAL)
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
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813162f0)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff813162f0-ffffffff81316365: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306ee0)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81306ee0-ffffffff81306f55: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813140e0)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff813140e0-ffffffff81314155: vfs_clean_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfs_clean_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325930)
Location: fs/fs_context.c:720
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81325930-ffffffff813259a5: vfs_clean_context (STB_GLOBAL)
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
