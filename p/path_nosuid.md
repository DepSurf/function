# Function: <code>path_nosuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212020)
Location: fs/exec.c:110
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81212020-ffffffff81212055: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81238af0)
Location: fs/exec.c:111
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81238af0-ffffffff81238b25: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124b7a0)
Location: fs/exec.c:111
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8124b7a0-ffffffff8124b7d5: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812578d0)
Location: fs/exec.c:116
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812578d0-ffffffff81257905: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81279ba0)
Location: fs/exec.c:116
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81279ba0-ffffffff81279bd5: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a0780)
Location: fs/exec.c:116
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812a0780-ffffffff812a07b5: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b5760)
Location: fs/exec.c:116
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812b5760-ffffffff812b5795: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d2510)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812d2510-ffffffff812d2547: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4020)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812e4020-ffffffff812e4057: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131c0f5)
Location: fs/exec.c:116
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
**Symbols:**

```
ffffffff8131b450-ffffffff8131b48a: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813275e5)
Location: fs/exec.c:119
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
**Symbols:**

```
ffffffff81326a80-ffffffff81326aba: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038bb80)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffff80001038bb80-ffff80001038bbd4: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c05740c0)
Location: fs/exec.c:117
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
Direct callers:
  - security/commoncap.c:cap_bprm_set_creds
  - security/selinux/hooks.c:check_nnp_nosuid
```
**Symbols:**

```
c05737cc-c0573808: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0000000004830e0)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c0000000004830e0-c000000000483158: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025cfcc)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffe00025cfcc-ffffffe00025d00e: path_nosuid (STB_GLOBAL)
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
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dc600)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812dc600-ffffffff812dc637: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cd280)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812cd280-ffffffff812cd2b7: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812da410)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812da410-ffffffff812da447: path_nosuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool path_nosuid(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812eb2b0)
Location: fs/exec.c:117
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff812eb2b0-ffffffff812eb2e7: path_nosuid (STB_GLOBAL)
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
