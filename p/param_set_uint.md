# Function: <code>param_set_uint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109ee70)
Location: kernel/params.c:295
Inline: False
Direct callers:
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff8109ee70-ffffffff8109ee86: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a2530)
Location: kernel/params.c:295
Inline: False
Direct callers:
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff810a2530-ffffffff810a2546: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a75f0)
Location: kernel/params.c:295
Inline: False
Direct callers:
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff810a75f0-ffffffff810a7606: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a4530)
Location: kernel/params.c:243
Inline: False
```
**Symbols:**

```
ffffffff810a4530-ffffffff810a4546: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810aab80)
Location: kernel/params.c:251
Inline: False
```
**Symbols:**

```
ffffffff810aab80-ffffffff810aab96: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810b17f0)
Location: kernel/params.c:251
Inline: False
```
**Symbols:**

```
ffffffff810b17f0-ffffffff810b1806: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810ba930)
Location: kernel/params.c:251
Inline: False
```
**Symbols:**

```
ffffffff810ba930-ffffffff810ba946: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0840)
Location: kernel/params.c:239
Inline: False
```
**Symbols:**

```
ffffffff810c0840-ffffffff810c0856: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c6c40)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffffffff810c6c40-ffffffff810c6c56: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cec60)
Location: kernel/params.c:240
Inline: False
Direct callers:
  - fs/fuse/inode.c:set_global_limit
```
**Symbols:**

```
ffffffff810cec60-ffffffff810cec76: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c9790)
Location: kernel/params.c:240
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
```
**Symbols:**

```
ffffffff810c9790-ffffffff810c97a6: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cb2a0)
Location: kernel/params.c:240
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
```
**Symbols:**

```
ffffffff810cb2a0-ffffffff810cb2b6: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810de380)
Location: kernel/params.c:240
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
```
**Symbols:**

```
ffffffff810de380-ffffffff810de396: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f80a0)
Location: kernel/params.c:240
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
```
**Symbols:**

```
ffffffff810f80a0-ffffffff810f80c0: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111aa50)
Location: kernel/params.c:240
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff8111aa50-ffffffff8111aa70: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81127cc0)
Location: kernel/params.c:241
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff81127cc0-ffffffff81127ce0: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811322a0)
Location: kernel/params.c:238
Inline: True
Direct callers:
  - fs/fuse/inode.c:set_global_limit
  - security/apparmor/lsm.c:param_set_aauint
```
**Symbols:**

```
ffffffff811322a0-ffffffff811322c0: param_set_uint (STB_GLOBAL)
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
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff800010125a70)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffff800010125a70-ffff800010125aa8: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c03786b4)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
c03786b4-c03786dc: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c00000000016f970)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
c00000000016f970-c00000000016f9b0: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000dd6a8)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffffffe0000dd6a8-ffffffe0000dd6de: param_set_uint (STB_GLOBAL)
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
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0fc0)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffffffff810c0fc0-ffffffff810c0fd6: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810af7b0)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffffffff810af7b0-ffffffff810af7c6: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c0510)
Location: kernel/params.c:240
Inline: False
Direct callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_set_hashsize
```
**Symbols:**

```
ffffffff810c0510-ffffffff810c0526: param_set_uint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int param_set_uint(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c8940)
Location: kernel/params.c:240
Inline: False
```
**Symbols:**

```
ffffffff810c8940-ffffffff810c8956: param_set_uint (STB_GLOBAL)
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
