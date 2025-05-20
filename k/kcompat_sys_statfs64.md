# Function: <code>kcompat_sys_statfs64</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea900)
Location: fs/statfs.c:338
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff812ea900-ffffffff812ea968: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81309370)
Location: fs/statfs.c:352
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81309370-ffffffff813093da: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c3e0)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff8131c3e0-ffffffff8131c44a: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81356100)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81356100-ffffffff81356168: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81362a40)
Location: fs/statfs.c:345
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81362a40-ffffffff81362aa8: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813694e0)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff813694e0-ffffffff81369548: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b81e0)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__x64_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff813b81e0-ffffffff813b8248: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143da90)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff8143da90-ffffffff8143db1b: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cc3f0)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff814cc3f0-ffffffff814cc47b: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81502630)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81502630-ffffffff815026bb: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81537280)
Location: fs/statfs.c:348
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81537280-ffffffff8153730b: kcompat_sys_statfs64 (STB_GLOBAL)
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
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3d68)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_statfs64
  - fs/statfs.c:__arm64_compat_sys_statfs64
```
**Symbols:**

```
ffff8000103d3d68-ffff8000103d3df4: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6860)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__se_compat_sys_statfs64
```
**Symbols:**

```
c0000000004d6860-c0000000004d690c: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813149c0)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff813149c0-ffffffff81314a2a: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813055d0)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff813055d0-ffffffff8130563a: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813127b0)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff813127b0-ffffffff8131281a: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kcompat_sys_statfs64(const char *pathname, compat_size_t sz, struct compat_statfs64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323ff0)
Location: fs/statfs.c:343
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
**Symbols:**

```
ffffffff81323ff0-ffffffff8132405a: kcompat_sys_statfs64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
