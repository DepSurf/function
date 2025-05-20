# Function: <code>register_sysctl_paths</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812862f0)
Location: fs/proc/proc_sysctl.c:1485
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff812862f0-ffffffff8128630d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b34b9)
Location: fs/proc/proc_sysctl.c:1491
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff812b3490-ffffffff812b34ad: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c8d09)
Location: fs/proc/proc_sysctl.c:1497
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff812c8ce0-ffffffff812c8cfd: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d6079)
Location: fs/proc/proc_sysctl.c:1561
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff812d6050-ffffffff812d606d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812fa8b9)
Location: fs/proc/proc_sysctl.c:1562
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff812fa890-ffffffff812fa8ad: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81327a65)
Location: fs/proc/proc_sysctl.c:1564
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_add_hooks
```
**Symbols:**

```
ffffffff81327a40-ffffffff81327a5d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133ebf5)
Location: fs/proc/proc_sysctl.c:1563
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff8133ebd0-ffffffff8133ebed: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366f25)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81366f00-ffffffff81366f1d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137f1b5)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff8137f190-ffffffff8137f1ad: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c9245)
Location: fs/proc/proc_sysctl.c:1571
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff813c9220-ffffffff813c923d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813db239)
Location: fs/proc/proc_sysctl.c:1571
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff813db210-ffffffff813db22d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e2169)
Location: fs/proc/proc_sysctl.c:1575
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff813e2140-ffffffff813e215d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433c79)
Location: fs/proc/proc_sysctl.c:1575
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81433c50-ffffffff81433c6d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814adc59)
Location: fs/proc/proc_sysctl.c:1635
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_base
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff814adbf0-ffffffff814adc17: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81544189)
Location: fs/proc/proc_sysctl.c:1634
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_base
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81544100-ffffffff81544127: register_sysctl_paths (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044c788)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffff80001044c730-ffff80001044c76c: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c06111e8)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
c06111a8-c06111d4: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000564040)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
c000000000564000-c000000000564028: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e1808)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffe0002e17b8-ffffffe0002e17f2: register_sysctl_paths (STB_GLOBAL)
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
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81377795)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81377770-ffffffff8137778d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81368265)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81368240-ffffffff8136825d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375265)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81375240-ffffffff8137525d: register_sysctl_paths (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_paths(const struct ctl_path *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81388c35)
Location: fs/proc/proc_sysctl.c:1588
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:register_sysctl_table
Direct callers:
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/seccomp.c:seccomp_sysctl_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
```
**Symbols:**

```
ffffffff81388c10-ffffffff81388c2d: register_sysctl_paths (STB_GLOBAL)
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
