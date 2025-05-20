# Function: <code>setup_userns_sysctls</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad6b0)
Location: kernel/ucount.c:81
Inline: False
Direct callers:
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810ad6b0-ffffffff810ad775: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa290)
Location: kernel/ucount.c:86
Inline: False
Direct callers:
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810aa290-ffffffff810aa355: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b0af0)
Location: kernel/ucount.c:86
Inline: False
Direct callers:
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810b0af0-ffffffff810b0bb5: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7900)
Location: kernel/ucount.c:87
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810b7900-ffffffff810b79b8: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0a00)
Location: kernel/ucount.c:87
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810c0a00-ffffffff810c0ab8: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6b00)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810c6b00-ffffffff810c6bbb: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfbd0)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810cfbd0-ffffffff810cfc8b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9c60)
Location: kernel/ucount.c:81
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810d9c60-ffffffff810d9d1b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4e10)
Location: kernel/ucount.c:81
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810d4e10-ffffffff810d4ecb: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6860)
Location: kernel/ucount.c:91
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810d6860-ffffffff810d691b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810e9d70)
Location: kernel/ucount.c:98
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810e9d70-ffffffff810e9e26: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff811049f0)
Location: kernel/ucount.c:98
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff811049f0-ffffffff81104aaf: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8112a280)
Location: kernel/ucount.c:94
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff8112a280-ffffffff8112a379: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff811372d0)
Location: kernel/ucount.c:94
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff811372d0-ffffffff811373c9: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff811424b0)
Location: kernel/ucount.c:94
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff811424b0-ffffffff811425ae: setup_userns_sysctls (STB_GLOBAL)
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
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff800010130128)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffff800010130128-ffff8000101301ec: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037f960)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
c037f960-c037fa18: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c0000000001795d0)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
c0000000001795d0-c0000000001796e0: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e363a)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffe0000e363a-ffffffe0000e36f2: setup_userns_sysctls (STB_GLOBAL)
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
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9f50)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810c9f50-ffffffff810ca00b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8770)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810b8770-ffffffff810b882b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c9480)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810c9480-ffffffff810c953b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool setup_userns_sysctls(struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d19e0)
Location: kernel/ucount.c:80
Inline: False
Direct callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/user_namespace.c:create_user_ns
```
**Symbols:**

```
ffffffff810d19e0-ffffffff810d1a9b: setup_userns_sysctls (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
