# Function: <code>find_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108c730)
Location: kernel/user.c:146
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
```
**Symbols:**

```
ffffffff8108c730-ffffffff8108c780: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8108f7a0)
Location: kernel/user.c:146
Inline: False
Direct callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff8108f7a0-ffffffff8108f7f0: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81094720)
Location: kernel/user.c:146
Inline: False
Direct callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff81094720-ffffffff81094770: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81091810)
Location: kernel/user.c:147
Inline: False
Direct callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff81091810-ffffffff81091860: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810986a0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
```
**Symbols:**

```
ffffffff810986a0-ffffffff810986f0: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8109bde0)
Location: kernel/user.c:154
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff8109bde0-ffffffff8109be30: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a3fe0)
Location: kernel/user.c:154
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810a3fe0-ffffffff810a4030: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8cb0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810a8cb0-ffffffff810a8d06: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810af280)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810af280-ffffffff810af2d6: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b6f90)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810b6f90-ffffffff810b6fe6: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b2150)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810b2150-ffffffff810b21a6: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b3790)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810b3790-ffffffff810b37e6: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810c5930)
Location: kernel/user.c:167
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810c5930-ffffffff810c5986: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810dcf20)
Location: kernel/user.c:167
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810dcf20-ffffffff810dcf78: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810fd2f0)
Location: kernel/user.c:167
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810fd2f0-ffffffff810fd348: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81109320)
Location: kernel/user.c:167
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff81109320-ffffffff81109378: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81112cb0)
Location: kernel/user.c:180
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff81112cb0-ffffffff81112d08: find_user (STB_GLOBAL)
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
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffff80001010a2e0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
```
**Symbols:**

```
ffff80001010a2e0-ffff80001010a3a8: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (c0363398)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c0363398-c03633fc: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (c000000000151220)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
c000000000151220-c0000000001512e8: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffe0000ccdc0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
```
**Symbols:**

```
ffffffe0000ccdc0-ffffffe0000cce40: find_user (STB_GLOBAL)
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
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a95f0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810a95f0-ffffffff810a9646: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81097fb0)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff81097fb0-ffffffff81098006: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8b50)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810a8b50-ffffffff810a8ba6: find_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct user_struct *find_user(kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b0c50)
Location: kernel/user.c:153
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
```
**Symbols:**

```
ffffffff810b0c50-ffffffff810b0ca6: find_user (STB_GLOBAL)
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
