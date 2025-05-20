# Function: <code>path_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request, bool delegate_deleted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81387d50)
Location: security/apparmor/file.c:167
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81387d50-ffffffff81387e78: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c2820)
Location: security/apparmor/file.c:168
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff813c2820-ffffffff813c2905: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813d9cc0)
Location: security/apparmor/file.c:168
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff813d9cc0-ffffffff813d9da5: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eae80)
Location: security/apparmor/file.c:170
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff813eae80-ffffffff813eaf57: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814127c0)
Location: security/apparmor/file.c:170
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff814127c0-ffffffff81412897: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff81444b60)
Location: security/apparmor/file.c:170
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff81444b60-ffffffff81444c37: path_name.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff81461a40)
Location: security/apparmor/file.c:171
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff81461a40-ffffffff81461b17: path_name.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff8148ed00)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff8148ed00-ffffffff8148eddd: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff814a8bc0)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff814a8bc0-ffffffff814a8c9d: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff815061b0)
Location: security/apparmor/file.c:167
Inline: False
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff815061b0-ffffffff8150628d: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff815232e0)
Location: security/apparmor/file.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff815232e0-ffffffff815233bd: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff815294d0)
Location: security/apparmor/file.c:158
Inline: False
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff815294d0-ffffffff815295ad: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81587870)
Location: security/apparmor/file.c:158
Inline: False
Direct callers:
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81587870-ffffffff8158794d: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81627fc0)
Location: security/apparmor/file.c:159
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_perm
```
**Symbols:**

```
ffffffff81627fc0-ffffffff816280a9: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int path_name(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dc6a0)
Location: security/apparmor/file.c:280
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff816dc6a0-ffffffff816dc797: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int path_name(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81715cb0)
Location: security/apparmor/file.c:300
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff81715cb0-ffffffff81715da7: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int path_name(const char *op, const struct cred *subj_cred, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff817547a0)
Location: security/apparmor/file.c:302
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:aa_path_perm
```
**Symbols:**

```
ffffffff817547a0-ffffffff81754897: path_name (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffff80001059f4d0)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffff80001059f4d0-ffff80001059f610: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int path_name(const char *op, struct aa_label *label, const struct path *path, int flags, char *buffer, const char **name, struct path_cond *cond, u32 request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c0750190)
Location: security/apparmor/file.c:167
Inline: False
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
c0750190-c07502cc: path_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (c000000000719370)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
c000000000719370-c000000000719518: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffe0003ea794)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffe0003ea794-ffffffe0003ea870: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff814a11a0)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff814a11a0-ffffffff814a127d: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff81491bc0)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff81491bc0-ffffffff81491c9d: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff8149d240)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff8149d240-ffffffff8149d31d: path_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (ffffffff814b57e0)
Location: security/apparmor/file.c:167
Inline: True
Direct callers:
  - security/apparmor/file.c:profile_path_link
  - security/apparmor/file.c:profile_path_link
```
**Symbols:**

```
ffffffff814b57e0-ffffffff814b58bd: path_name.isra.0 (STB_LOCAL)
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
<b>Param removed. </b>
<code>bool delegate_deleted</code>
</li>
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
<b>Param reordered. </b>
<code>op, label, path, flags, buffer, name, cond, request</code> ➡️ <code>op, subj_cred, label, path, flags, buffer, name, cond, request</code>
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
</ul>
