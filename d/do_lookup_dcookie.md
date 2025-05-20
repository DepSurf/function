# Function: <code>do_lookup_dcookie</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff81335440)
Location: fs/dcookies.c:149
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff81335440-ffffffff813355aa: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff8134c6c0)
Location: fs/dcookies.c:149
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff8134c6c0-ffffffff8134c82a: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff813750d0)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff813750d0-ffffffff81375243: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff8138d350)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff8138d350-ffffffff8138d4ce: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff813d8a50)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff813d8a50-ffffffff813d8bd4: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff813ea650)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff813ea650-ffffffff813ea7d4: do_lookup_dcookie (STB_LOCAL)
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
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffff80001045f390)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__arm64_compat_sys_lookup_dcookie
  - fs/dcookies.c:__arm64_sys_lookup_dcookie
```
**Symbols:**

```
ffff80001045f390-ffff80001045f650: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (c061fcb0)
Location: fs/dcookies.c:150
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (c00000000057b2c0)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__se_compat_sys_lookup_dcookie
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
**Symbols:**

```
c00000000057b2c0-c00000000057b4e8: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffe0002eedd0)
Location: fs/dcookies.c:150
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
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
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff81385930)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff81385930-ffffffff81385aae: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff813763c0)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff813763c0-ffffffff8137653e: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff81383400)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff81383400-ffffffff8138357e: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_lookup_dcookie(u64 cookie64, char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (ffffffff81396f20)
Location: fs/dcookies.c:150
Inline: False
Direct callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_sys_lookup_dcookie
  - fs/dcookies.c:__x64_sys_lookup_dcookie
```
**Symbols:**

```
ffffffff81396f20-ffffffff8139709e: do_lookup_dcookie (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
