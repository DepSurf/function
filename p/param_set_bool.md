# Function: <code>param_set_bool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109efe0)
Location: kernel/params.c:343
Inline: True
Inline callers:
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bint
Direct callers:
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff8109efe0-ffffffff8109f002: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a27dd)
Location: kernel/params.c:343
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810a26a0-ffffffff810a26c2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a789d)
Location: kernel/params.c:343
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff810a7760-ffffffff810a7782: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a48ed)
Location: kernel/params.c:291
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff810a47b0-ffffffff810a47d2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810aaf3d)
Location: kernel/params.c:299
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff810aae00-ffffffff810aae22: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810b1a04)
Location: kernel/params.c:299
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff810b18b0-ffffffff810b18d2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810bab44)
Location: kernel/params.c:299
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff810ba9f0-ffffffff810baa12: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0a64)
Location: kernel/params.c:287
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810c0910-ffffffff810c0932: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c6e64)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810c6d10-ffffffff810c6d32: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cee64)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff810ced10-ffffffff810ced32: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c9994)
Location: kernel/params.c:289
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff810c9840-ffffffff810c9862: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cb4a4)
Location: kernel/params.c:289
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff810cb350-ffffffff810cb372: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810de856)
Location: kernel/params.c:307
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff810de4b0-ffffffff810de4d2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f88c4)
Location: kernel/params.c:307
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/memory_hotplug.c:memmap_on_memory_set
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff810f8380-ffffffff810f83aa: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111b3a4)
Location: kernel/params.c:307
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_param_set
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff8111add0-ffffffff8111adfa: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811285f4)
Location: kernel/params.c:308
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff81128040-ffffffff8112806a: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81132c14)
Location: kernel/params.c:310
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
```
**Symbols:**

```
ffffffff81132660-ffffffff8113268a: param_set_bool (STB_GLOBAL)
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
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff800010125d60)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffff800010125bc0-ffff800010125c00: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378a5c)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
c03788c4-c03788f4: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (c00000000016fec4)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
c00000000016fc80-c00000000016fce4: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000dd914)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffe0000dd7f0-ffffffe0000dd830: param_set_bool (STB_GLOBAL)
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
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c11e4)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810c1090-ffffffff810c10b2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810af9d4)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810af880-ffffffff810af8a2: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0734)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810c05e0-ffffffff810c0602: param_set_bool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int param_set_bool(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c8c04)
Location: kernel/params.c:288
Inline: True
Inline callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
Direct callers:
  - mm/shuffle.c:shuffle_store
  - mm/zswap.c:zswap_enabled_param_set
  - security/apparmor/lsm.c:param_set_aaintbool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff810c8ab0-ffffffff810c8ad2: param_set_bool (STB_GLOBAL)
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
