# Function: <code>efivarfs_valid_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81320de0)
Location: fs/efivarfs/inode.c:47
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81320de0-ffffffff81320e45: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8135645a)
Location: fs/efivarfs/inode.c:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff813565a0-ffffffff813565c7: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8136c87a)
Location: fs/efivarfs/inode.c:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff8136c9f0-ffffffff8136ca17: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81380dba)
Location: fs/efivarfs/inode.c:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81380f30-ffffffff81380f57: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813a5dca)
Location: fs/efivarfs/inode.c:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff813a5f40-ffffffff813a5f67: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813d5079)
Location: fs/efivarfs/inode.c:48
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff813d5200-ffffffff813d5226: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813ef6ca)
Location: fs/efivarfs/inode.c:48
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff813ef850-ffffffff813ef876: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8141b9ba)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff8141bb40-ffffffff8141bb66: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8143580a)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81435990-ffffffff814359b6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8148551a)
Location: fs/efivarfs/inode.c:45
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff814856a0-ffffffff814856c6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a2b4a)
Location: fs/efivarfs/inode.c:46
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff814a2cd0-ffffffff814a2cf6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a8d41)
Location: fs/efivarfs/inode.c:50
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff814a8ec0-ffffffff814a8ee6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81501071)
Location: fs/efivarfs/inode.c:50
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81501250-ffffffff81501276: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff815923d0)
Location: fs/efivarfs/inode.c:50
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff815925c0-ffffffff815925f6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81639d2d)
Location: fs/efivarfs/inode.c:50
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81639f70-ffffffff81639fa6: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8167218d)
Location: fs/efivarfs/inode.c:50
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff816723d0-ffffffff81672406: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff816ae176)
Location: fs/efivarfs/inode.c:54
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff816ae410-ffffffff816ae446: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffff80001051b728)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffff80001051b8d0-ffff80001051b930: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (c06d8144)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
c06d82cc-c06d830c: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8142ddea)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff8142df70-ffffffff8142df96: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8141e86a)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff8141e9f0-ffffffff8141ea16: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81429f8a)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff8142a110-ffffffff8142a136: efivarfs_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool efivarfs_valid_name(const char *str, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81440e4a)
Location: fs/efivarfs/inode.c:45
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
**Symbols:**

```
ffffffff81440fd0-ffffffff81440ff6: efivarfs_valid_name (STB_GLOBAL)
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
