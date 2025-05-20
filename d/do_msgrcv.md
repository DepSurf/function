# Function: <code>do_msgrcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81326590)
Location: ipc/msg.c:825
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/msg.c:SyS_msgrcv
```
**Symbols:**

```
ffffffff81326590-ffffffff81326b25: do_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8135b1e0)
Location: ipc/msg.c:825
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgrcv
```
**Symbols:**

```
ffffffff8135b1e0-ffffffff8135b777: do_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81371800)
Location: ipc/msg.c:849
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgrcv
```
**Symbols:**

```
ffffffff81371800-ffffffff81371d9d: do_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81384bb0)
Location: ipc/msg.c:849
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_msgrcv
  - ipc/compat.c:compat_SyS_ipc
  - ipc/msg.c:SyS_msgrcv
```
**Symbols:**

```
ffffffff81384bb0-ffffffff81385186: do_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8ea0)
Location: ipc/msg.c:972
Inline: False
Direct callers:
  - ipc/msg.c:compat_SyS_msgrcv
  - ipc/msg.c:SyS_msgrcv
```
**Symbols:**

```
ffffffff813a8ea0-ffffffff813a9457: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d86f0)
Location: ipc/msg.c:1031
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff813d86f0-ffffffff813d8c75: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f2570)
Location: ipc/msg.c:1041
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff813f2570-ffffffff813f2af5: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141f490)
Location: ipc/msg.c:1066
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff8141f490-ffffffff8141fa92: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814392b0)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff814392b0-ffffffff814398b2: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81489370)
Location: ipc/msg.c:1090
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81489370-ffffffff81489a02: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a6990)
Location: ipc/msg.c:1090
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff814a6990-ffffffff814a7040: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac900)
Location: ipc/msg.c:1092
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff814ac900-ffffffff814acf77: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:1092
Inline: False
Direct callers:
  - ipc/msg.c:__x64_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81504de0-ffffffff81505465: do_msgrcv (STB_LOCAL)
ffffffff81cd29dd-ffffffff81cd29f1: do_msgrcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:1092
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81596740-ffffffff81596e3e: do_msgrcv (STB_LOCAL)
ffffffff81e85b37-ffffffff81e85b4c: do_msgrcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:1098
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff8163f640-ffffffff8163fd7d: do_msgrcv (STB_LOCAL)
ffffffff82072d35-ffffffff82072d4a: do_msgrcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:1098
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81677b70-ffffffff816782a0: do_msgrcv (STB_LOCAL)
ffffffff820f298c-ffffffff820f29a1: do_msgrcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:1098
Inline: False
Direct callers:
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff816b3f30-ffffffff816b4660: do_msgrcv (STB_LOCAL)
ffffffff821cfc3c-ffffffff821cfc51: do_msgrcv.cold (STB_LOCAL)
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
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051f840)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__arm64_compat_sys_msgrcv
  - ipc/msg.c:__arm64_sys_msgrcv
```
**Symbols:**

```
ffff80001051f840-ffff80001051fd74: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (c06db0d0)
Location: ipc/msg.c:1067
Inline: True
Direct callers:
  - ipc/msg.c:__se_sys_msgrcv
```
**Symbols:**

```
c06db0d0-c06db638: do_msgrcv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669bf0)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__se_compat_sys_msgrcv
  - ipc/msg.c:__se_sys_msgrcv
```
**Symbols:**

```
c000000000669bf0-c00000000066a33c: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (ffffffe000386900)
Location: ipc/msg.c:1067
Inline: True
Direct callers:
  - ipc/msg.c:__se_sys_msgrcv
```
**Symbols:**

```
ffffffe000386900-ffffffe000386dc0: do_msgrcv.constprop.0 (STB_LOCAL)
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
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81431890)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81431890-ffffffff81431e92: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81422310)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81422310-ffffffff81422912: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142da30)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff8142da30-ffffffff8142e032: do_msgrcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void *buf, size_t bufsz, long int msgtyp, int msgflg, long int (*msg_handler)(void *, struct msg_msg *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444460)
Location: ipc/msg.c:1067
Inline: False
Direct callers:
  - ipc/msg.c:__x32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_compat_sys_msgrcv
  - ipc/msg.c:__ia32_sys_msgrcv
  - ipc/msg.c:__x64_sys_msgrcv
```
**Symbols:**

```
ffffffff81444460-ffffffff81444a89: do_msgrcv (STB_LOCAL)
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
