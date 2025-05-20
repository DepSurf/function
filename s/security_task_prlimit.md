# Function: <code>security_task_prlimit</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fac0)
Location: security/security.c:1648
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prlimit64
```
**Symbols:**

```
ffffffff8139fac0-ffffffff8139fb1b: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c56e0)
Location: security/security.c:1610
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prlimit64
```
**Symbols:**

```
ffffffff813c56e0-ffffffff813c5741: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5730)
Location: security/security.c:1114
Inline: False
Direct callers:
  - kernel/sys.c:check_prlimit_permission
```
**Symbols:**

```
ffffffff813f5730-ffffffff813f577e: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410d60)
Location: security/security.c:1722
Inline: False
Direct callers:
  - kernel/sys.c:check_prlimit_permission
```
**Symbols:**

```
ffffffff81410d60-ffffffff81410dae: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e550)
Location: security/security.c:1741
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff8143e550-ffffffff8143e5a7: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457fa0)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff81457fa0-ffffffff81457fec: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aae30)
Location: security/security.c:1976
Inline: False
Direct callers:
  - kernel/sys.c:check_prlimit_permission
```
**Symbols:**

```
ffffffff814aae30-ffffffff814aae7c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8430)
Location: security/security.c:1993
Inline: False
Direct callers:
  - kernel/sys.c:check_prlimit_permission
```
**Symbols:**

```
ffffffff814c8430-ffffffff814c847c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cea70)
Location: security/security.c:2056
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff814cea70-ffffffff814ceabc: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527730)
Location: security/security.c:2064
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff81527730-ffffffff8152777c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc590)
Location: security/security.c:2070
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff815bc590-ffffffff815bc5fb: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816685d0)
Location: security/security.c:2122
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff816685d0-ffffffff8166863b: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0c20)
Location: security/security.c:3475
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff816a0c20-ffffffff816a0c8b: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd5f0)
Location: security/security.c:3534
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prlimit64
```
**Symbols:**

```
ffffffff816dd5f0-ffffffff816dd65b: security_task_prlimit (STB_GLOBAL)
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
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543d28)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prlimit64
```
**Symbols:**

```
ffff800010543d28-ffff800010543d8c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9c7c)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prlimit64
```
**Symbols:**

```
c06f9c7c-c06f9ce0: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698400)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prlimit64
```
**Symbols:**

```
c000000000698400-c0000000006984d0: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a009c)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prlimit64
```
**Symbols:**

```
ffffffe0003a009c-ffffffe0003a00e8: security_task_prlimit (STB_GLOBAL)
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
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450580)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff81450580-ffffffff814505cc: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440fd0)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff81440fd0-ffffffff8144101c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c620)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff8144c620-ffffffff8144c66c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814639f0)
Location: security/security.c:1780
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
**Symbols:**

```
ffffffff814639f0-ffffffff81463a3c: security_task_prlimit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
