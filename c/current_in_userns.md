# Function: <code>current_in_userns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111f480)
Location: kernel/user_namespace.c:958
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8111f480-ffffffff8111f4ca: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81126270)
Location: kernel/user_namespace.c:951
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81126270-ffffffff811262ba: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112fcc0)
Location: kernel/user_namespace.c:997
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8112fcc0-ffffffff8112fd0a: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811312d0)
Location: kernel/user_namespace.c:998
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff811312d0-ffffffff8113131a: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113de40)
Location: kernel/user_namespace.c:1240
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8113de40-ffffffff8113de85: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114c7e0)
Location: kernel/user_namespace.c:1237
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8114c7e0-ffffffff8114c825: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81159400)
Location: kernel/user_namespace.c:1241
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81159400-ffffffff81159445: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81165b40)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81165b40-ffffffff81165b85: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171a00)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81171a00-ffffffff81171a45: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183820)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff81183820-ffffffff81183865: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81180750)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
```
**Symbols:**

```
ffffffff81180750-ffffffff81180795: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811817b0)
Location: kernel/user_namespace.c:1294
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff811817b0-ffffffff811817f5: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a96d0)
Location: kernel/user_namespace.c:1310
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
```
**Symbols:**

```
ffffffff811a96d0-ffffffff811a9715: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811daac0)
Location: kernel/user_namespace.c:1315
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff811daac0-ffffffff811dab0d: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81220150)
Location: kernel/user_namespace.c:1315
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
```
**Symbols:**

```
ffffffff81220150-ffffffff8122019d: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812363c0)
Location: kernel/user_namespace.c:1315
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff812363c0-ffffffff8123640d: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81250040)
Location: kernel/user_namespace.c:1318
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - fs/fuse/dir.c:fuse_allow_current_process
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff81250040-ffffffff8125008d: current_in_userns (STB_GLOBAL)
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
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e57e0)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffff8000101e57e0-ffff8000101e583c: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0425f68)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c0425f68-c0425fc4: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000255bd0)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c000000000255bd0-c000000000255c20: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b2d0)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffe00015b2d0-ffffffe00015b314: current_in_userns (STB_GLOBAL)
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
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a020)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8116a020-ffffffff8116a065: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d220)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8115d220-ffffffff8115d265: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81167df0)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81167df0-ffffffff81167e35: current_in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool current_in_userns(const struct user_namespace *target_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811754d0)
Location: kernel/user_namespace.c:1235
Inline: False
Direct callers:
  - fs/namespace.c:mnt_may_suid
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff811754d0-ffffffff81175515: current_in_userns (STB_GLOBAL)
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
