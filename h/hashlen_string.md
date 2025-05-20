# Function: <code>hashlen_string</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f190)
Location: fs/namei.c:1930
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
```
**Symbols:**

```
ffffffff8123f190-ffffffff8123f230: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251f60)
Location: fs/namei.c:1923
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
```
**Symbols:**

```
ffffffff81251f60-ffffffff81252000: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125dae0)
Location: fs/namei.c:1933
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff8125dae0-ffffffff8125db80: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127fe30)
Location: fs/namei.c:1931
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff8127fe30-ffffffff8127fed0: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a63d0)
Location: fs/namei.c:1918
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812a63d0-ffffffff812a6470: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ba1b0)
Location: fs/namei.c:1959
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812ba1b0-ffffffff812ba250: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d80a0)
Location: fs/namei.c:1957
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812d80a0-ffffffff812d8140: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9c10)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812e9c10-ffffffff812e9cb0: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321db0)
Location: fs/namei.c:1996
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81321db0-ffffffff81321e52: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d370)
Location: fs/namei.c:1992
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff8132d370-ffffffff8132d412: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332e60)
Location: fs/namei.c:2078
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81332e60-ffffffff81332f08: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813805f0)
Location: fs/namei.c:2106
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff813805f0-ffffffff81380698: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400490)
Location: fs/namei.c:2152
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81400490-ffffffff8140056f: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489900)
Location: fs/namei.c:2129
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81489900-ffffffff814899e0: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814be830)
Location: fs/namei.c:2134
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff814be830-ffffffff814be907: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f0cb0)
Location: fs/namei.c:2141
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff814f0cb0-ffffffff814f0d87: hashlen_string (STB_GLOBAL)
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
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010391cd8)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffff800010391cd8-ffff800010391d9c: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05783fc)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c05783fc-c057849c: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489c30)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c000000000489c30-c000000000489d00: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000260f02)
Location: fs/namei.c:2016
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffe000260f02-ffffffe000260f68: hashlen_string (STB_GLOBAL)
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
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e21f0)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812e21f0-ffffffff812e2290: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2e30)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812d2e30-ffffffff812d2ed0: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0000)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812e0000-ffffffff812e00a0: hashlen_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 hashlen_string(const void *salt, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1860)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_name
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812f1860-ffffffff812f1900: hashlen_string (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
