# Function: <code>selinux_task_prlimit</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a7bc0)
Location: security/selinux/hooks.c:3881
Inline: True
```
**Symbols:**

```
ffffffff813a7bc0-ffffffff813a7c0e: selinux_task_prlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cdcf0)
Location: security/selinux/hooks.c:3896
Inline: True
```
**Symbols:**

```
ffffffff813cdcf0-ffffffff813cdd3e: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb350)
Location: security/selinux/hooks.c:4123
Inline: True
```
**Symbols:**

```
ffffffff813fb350-ffffffff813fb3a3: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81417840)
Location: security/selinux/hooks.c:3843
Inline: True
```
**Symbols:**

```
ffffffff81417840-ffffffff8141789e: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445470)
Location: security/selinux/hooks.c:4031
Inline: True
```
**Symbols:**

```
ffffffff81445470-ffffffff814454d2: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145f000)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffff8145f000-ffffffff8145f062: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b25f0)
Location: security/selinux/hooks.c:4082
Inline: True
```
**Symbols:**

```
ffffffff814b25f0-ffffffff814b2652: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf970)
Location: security/selinux/hooks.c:4098
Inline: True
```
**Symbols:**

```
ffffffff814cf970-ffffffff814cf9d2: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6090)
Location: security/selinux/hooks.c:4262
Inline: True
```
**Symbols:**

```
ffffffff814d6090-ffffffff814d60ee: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152ec00)
Location: security/selinux/hooks.c:4247
Inline: True
```
**Symbols:**

```
ffffffff8152ec00-ffffffff8152ec5e: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c5680)
Location: security/selinux/hooks.c:4143
Inline: True
```
**Symbols:**

```
ffffffff815c5680-ffffffff815c5702: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81672280)
Location: security/selinux/hooks.c:4161
Inline: True
```
**Symbols:**

```
ffffffff81672280-ffffffff81672302: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816aa7c0)
Location: security/selinux/hooks.c:4128
Inline: True
```
**Symbols:**

```
ffffffff816aa7c0-ffffffff816aa827: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e7850)
Location: security/selinux/hooks.c:4216
Inline: True
```
**Symbols:**

```
ffffffff816e7850-ffffffff816e78bd: selinux_task_prlimit (STB_LOCAL)
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
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054c140)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffff80001054c140-ffff80001054c1cc: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c070241c)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
c070241c-c0702498: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4a50)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
c0000000006a4a50-c0000000006a4ae8: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a684c)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffe0003a684c-ffffffe0003a68c2: selinux_task_prlimit (STB_LOCAL)
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
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814575e0)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffff814575e0-ffffffff81457642: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448010)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffff81448010-ffffffff81448072: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81453680)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffff81453680-ffffffff814536e2: selinux_task_prlimit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_task_prlimit(const struct cred *cred, const struct cred *tcred, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146b180)
Location: security/selinux/hooks.c:4089
Inline: True
```
**Symbols:**

```
ffffffff8146b180-ffffffff8146b1e2: selinux_task_prlimit (STB_LOCAL)
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
