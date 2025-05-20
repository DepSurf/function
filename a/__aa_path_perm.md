# Function: <code>__aa_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81388300)
Location: security/apparmor/file.c:286
Inline: True
Direct callers:
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff81388300-ffffffff8138840d: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c2e60)
Location: security/apparmor/file.c:284
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813c2e60-ffffffff813c2f6d: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813da370)
Location: security/apparmor/file.c:284
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813da370-ffffffff813da47d: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eb4b0)
Location: security/apparmor/file.c:287
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff813eb4b0-ffffffff813eb5b1: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81412df0)
Location: security/apparmor/file.c:281
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff81412df0-ffffffff81412ef1: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81445190)
Location: security/apparmor/file.c:281
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81445190-ffffffff8144528e: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81462080)
Location: security/apparmor/file.c:282
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81462080-ffffffff8146217e: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8148f330)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8148f330-ffffffff8148f441: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a91f0)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814a91f0-ffffffff814a9301: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81506890)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81506890-ffffffff815069ff: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81523980)
Location: security/apparmor/file.c:267
Inline: True
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81523980-ffffffff81523aef: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81529b60)
Location: security/apparmor/file.c:269
Inline: True
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81529b60-ffffffff81529cc6: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81587f00)
Location: security/apparmor/file.c:269
Inline: True
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81587f00-ffffffff81588066: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628560)
Location: security/apparmor/file.c:225
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_perm
```
**Symbols:**

```
ffffffff81628560-ffffffff81628679: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms, bool prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dccb0)
Location: security/apparmor/file.c:348
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff816dccb0-ffffffff816dcdde: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms, bool prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff817162b0)
Location: security/apparmor/file.c:368
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff817162b0-ffffffff817163d9: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __aa_path_perm(const char *op, const struct cred *subj_cred, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms, bool prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81754d60)
Location: security/apparmor/file.c:375
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81754d60-ffffffff81754e94: __aa_path_perm (STB_GLOBAL)
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
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffff80001059fb50)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffff80001059fb50-ffff80001059fc6c: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c07507f4)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
c07507f4-c0750910: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c000000000719b30)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
c000000000719b30-c000000000719cdc: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffe0003ead3c)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffe0003ead3c-ffffffe0003eae08: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814a17d0)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814a17d0-ffffffff814a18e1: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814921f0)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814921f0-ffffffff81492301: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff8149d870)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff8149d870-ffffffff8149d981: __aa_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __aa_path_perm(const char *op, struct aa_profile *profile, const char *name, u32 request, struct path_cond *cond, int flags, struct aa_perms *perms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814b5e10)
Location: security/apparmor/file.c:278
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff814b5e10-ffffffff814b5f21: __aa_path_perm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param added. </b>
<code>bool prompt</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, profile, name, request, cond, flags, perms</code> ➡️ <code>op, subj_cred, profile, name, request, cond, flags, perms, prompt</code>
</li>
</ul>
</details>
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
