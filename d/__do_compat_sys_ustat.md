# Function: <code>__do_compat_sys_ustat</code>

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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4e80)
Location: fs/statfs.c:371
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff812d4e80-ffffffff812d4f35: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea250)
Location: fs/statfs.c:381
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff812ea250-ffffffff812ea305: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308cb0)
Location: fs/statfs.c:395
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81308cb0-ffffffff81308d67: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131bd20)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff8131bd20-ffffffff8131bdd7: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813558a0)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff813558a0-ffffffff81355984: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813621c0)
Location: fs/statfs.c:388
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff813621c0-ffffffff813622a6: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368ca0)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81368ca0-ffffffff81368d82: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b79a0)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__x64_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff813b79a0-ffffffff813b7a82: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d0e0)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff8143d0e0-ffffffff8143d200: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb8b0)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff814cb8b0-ffffffff814cb9d0: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501af0)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81501af0-ffffffff81501c10: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536740)
Location: fs/statfs.c:391
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81536740-ffffffff81536860: __do_compat_sys_ustat (STB_LOCAL)
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d31f8)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__arm64_compat_sys_ustat
```
**Symbols:**

```
ffff8000103d31f8-ffff8000103d32e8: __do_compat_sys_ustat (STB_LOCAL)
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6040)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__se_compat_sys_ustat
```
**Symbols:**

```
c0000000004d6040-c0000000004d6118: __do_compat_sys_ustat (STB_LOCAL)
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314300)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81314300-ffffffff813143b7: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304f10)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81304f10-ffffffff81304fc7: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813120f0)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff813120f0-ffffffff813121a7: __do_compat_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323930)
Location: fs/statfs.c:386
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
**Symbols:**

```
ffffffff81323930-ffffffff813239e7: __do_compat_sys_ustat (STB_LOCAL)
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
