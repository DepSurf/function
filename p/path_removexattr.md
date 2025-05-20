# Function: <code>path_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81232280)
Location: fs/xattr.c:625
Inline: False
Direct callers:
  - fs/xattr.c:SyS_removexattr
  - fs/xattr.c:SyS_lremovexattr
```
**Symbols:**

```
ffffffff81232280-ffffffff8123232c: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125af90)
Location: fs/xattr.c:617
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lremovexattr
  - fs/xattr.c:SyS_removexattr
```
**Symbols:**

```
ffffffff8125af90-ffffffff8125b055: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e530)
Location: fs/xattr.c:722
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lremovexattr
  - fs/xattr.c:SyS_removexattr
```
**Symbols:**

```
ffffffff8126e530-ffffffff8126e5f5: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127bd30)
Location: fs/xattr.c:719
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lremovexattr
  - fs/xattr.c:SyS_removexattr
```
**Symbols:**

```
ffffffff8127bd30-ffffffff8127bde6: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e7d0)
Location: fs/xattr.c:720
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lremovexattr
  - fs/xattr.c:SyS_removexattr
```
**Symbols:**

```
ffffffff8129e7d0-ffffffff8129e886: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5280)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff812c5280-ffffffff812c5336: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812da480)
Location: fs/xattr.c:717
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff812da480-ffffffff812da536: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f8a60)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff812f8a60-ffffffff812f8b0f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130a690)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff8130a690-ffffffff8130a73f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343690)
Location: fs/xattr.c:788
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff81343690-ffffffff8134373f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f820)
Location: fs/xattr.c:820
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff8134f820-ffffffff8134f8cf: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356340)
Location: fs/xattr.c:848
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff81356340-ffffffff813563f7: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4870)
Location: fs/xattr.c:849
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff813a4870-ffffffff813a4927: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814288b0)
Location: fs/xattr.c:901
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff814288b0-ffffffff81428985: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b5ec0)
Location: fs/xattr.c:924
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff814b5ec0-ffffffff814b5f95: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814ea6f0)
Location: fs/xattr.c:921
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff814ea6f0-ffffffff814ea7c5: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151e590)
Location: fs/xattr.c:921
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff8151e590-ffffffff8151e668: path_removexattr (STB_LOCAL)
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
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103be0f0)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_lremovexattr
  - fs/xattr.c:__arm64_sys_removexattr
```
**Symbols:**

```
ffff8000103be0f0-ffff8000103be1c0: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b924)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lremovexattr
  - fs/xattr.c:__se_sys_removexattr
```
**Symbols:**

```
c059b924-c059b9f4: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bcbe0)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lremovexattr
  - fs/xattr.c:__se_sys_removexattr
```
**Symbols:**

```
c0000000004bcbe0-c0000000004bcd0c: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f4ee)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lremovexattr
  - fs/xattr.c:__se_sys_removexattr
```
**Symbols:**

```
ffffffe00027f4ee-ffffffe00027f58e: path_removexattr (STB_LOCAL)
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
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81302c70)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff81302c70-ffffffff81302d1f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f3890)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff812f3890-ffffffff812f393f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81300a60)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff81300a60-ffffffff81300b0f: path_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int path_removexattr(const char *pathname, const char *name, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311da0)
Location: fs/xattr.c:718
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lremovexattr
  - fs/xattr.c:__x64_sys_lremovexattr
  - fs/xattr.c:__ia32_sys_removexattr
  - fs/xattr.c:__x64_sys_removexattr
```
**Symbols:**

```
ffffffff81311da0-ffffffff81311e4f: path_removexattr (STB_LOCAL)
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
