# Function: <code>__do_compat_sys_statfs</code>

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
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d5230)
Location: fs/statfs.c:286
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff812d5230-ffffffff812d5289: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea600)
Location: fs/statfs.c:286
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff812ea600-ffffffff812ea659: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81309070)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81309070-ffffffff813090cb: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c0e0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff8131c0e0-ffffffff8131c13b: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355df0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81355df0-ffffffff81355e49: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81362730)
Location: fs/statfs.c:302
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81362730-ffffffff81362789: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813691d0)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff813691d0-ffffffff81369229: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7ed0)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__x64_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff813b7ed0-ffffffff813b7f29: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d710)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff8143d710-ffffffff8143d789: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cbfc0)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff814cbfc0-ffffffff814cc039: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81502200)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81502200-ffffffff81502279: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536e50)
Location: fs/statfs.c:305
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81536e50-ffffffff81536ec9: __do_compat_sys_statfs (STB_LOCAL)
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
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3a78)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__arm64_compat_sys_statfs
```
**Symbols:**

```
ffff8000103d3a78-ffff8000103d3adc: __do_compat_sys_statfs (STB_LOCAL)
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
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d64d0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__se_compat_sys_statfs
```
**Symbols:**

```
c0000000004d64d0-c0000000004d6548: __do_compat_sys_statfs (STB_LOCAL)
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
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813146c0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff813146c0-ffffffff8131471b: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813052d0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff813052d0-ffffffff8130532b: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813124b0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff813124b0-ffffffff8131250b: __do_compat_sys_statfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_statfs(const char *pathname, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323cf0)
Location: fs/statfs.c:300
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
**Symbols:**

```
ffffffff81323cf0-ffffffff81323d4b: __do_compat_sys_statfs (STB_LOCAL)
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
