# Function: <code>set_cred_ucounts</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d48c0)
Location: kernel/cred.c:668
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/cred.c:copy_creds
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810d48c0-ffffffff810d4961: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e7bc8)
Location: kernel/cred.c:666
Inline: True
Inline callers:
  - kernel/cred.c:copy_creds
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff810e7c60-ffffffff810e7cbc: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101e6b)
Location: kernel/cred.c:666
Inline: True
Inline callers:
  - kernel/cred.c:copy_creds
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81101f00-ffffffff81101f62: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81127078)
Location: kernel/cred.c:666
Inline: True
Inline callers:
  - kernel/cred.c:copy_creds
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81127120-ffffffff81127182: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81134518)
Location: kernel/cred.c:666
Inline: True
Inline callers:
  - kernel/cred.c:copy_creds
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff811345c0-ffffffff81134622: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_cred_ucounts(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113f4fd)
Location: kernel/cred.c:583
Inline: True
Inline callers:
  - kernel/cred.c:copy_creds
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/user_namespace.c:userns_install
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8113f590-ffffffff8113f5f2: set_cred_ucounts (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
