# Function: <code>security_task_fix_setuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e450)
Location: security/security.c:923
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setfsuid
```
**Symbols:**

```
ffffffff8133e450-ffffffff8133e4ab: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373a60)
Location: security/security.c:947
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
```
**Symbols:**

```
ffffffff81373a60-ffffffff81373abb: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a390)
Location: security/security.c:968
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
```
**Symbols:**

```
ffffffff8138a390-ffffffff8138a3eb: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f880)
Location: security/security.c:1605
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
```
**Symbols:**

```
ffffffff8139f880-ffffffff8139f8db: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5460)
Location: security/security.c:1567
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
```
**Symbols:**

```
ffffffff813c5460-ffffffff813c54c1: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5530)
Location: security/security.c:1071
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff813f5530-ffffffff813f557e: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410b60)
Location: security/security.c:1679
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81410b60-ffffffff81410bae: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e310)
Location: security/security.c:1698
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff8143e310-ffffffff8143e367: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457da0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81457da0-ffffffff81457dec: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aabe0)
Location: security/security.c:1921
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff814aabe0-ffffffff814aac2c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c81e0)
Location: security/security.c:1938
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff814c81e0-ffffffff814c822c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce820)
Location: security/security.c:1988
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff814ce820-ffffffff814ce86c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815274e0)
Location: security/security.c:1996
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff815274e0-ffffffff8152752c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc2a0)
Location: security/security.c:2001
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff815bc2a0-ffffffff815bc30b: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816681f0)
Location: security/security.c:2048
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff816681f0-ffffffff8166825b: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0840)
Location: security/security.c:3296
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff816a0840-ffffffff816a08ab: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd210)
Location: security/security.c:3368
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff816dd210-ffffffff816dd27b: security_task_fix_setuid (STB_GLOBAL)
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
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543ab0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffff800010543ab0-ffff800010543b14: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9a08)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
c06f9a08-c06f9a6c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697ee0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
c000000000697ee0-c000000000697fb0: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039fed0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffe00039fed0-ffffffe00039ff1c: security_task_fix_setuid (STB_GLOBAL)
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
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450380)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81450380-ffffffff814503cc: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440dd0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff81440dd0-ffffffff81440e1c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c420)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff8144c420-ffffffff8144c46c: security_task_fix_setuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814637f0)
Location: security/security.c:1737
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff814637f0-ffffffff8146383c: security_task_fix_setuid (STB_GLOBAL)
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
