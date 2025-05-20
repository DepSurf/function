# Function: <code>security_task_fix_setgid</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aac30)
Location: security/security.c:1927
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff814aac30-ffffffff814aac7c: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8230)
Location: security/security.c:1944
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff814c8230-ffffffff814c827c: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce870)
Location: security/security.c:1994
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff814ce870-ffffffff814ce8bc: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527530)
Location: security/security.c:2002
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff81527530-ffffffff8152757c: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc310)
Location: security/security.c:2007
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff815bc310-ffffffff815bc37b: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668270)
Location: security/security.c:2054
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff81668270-ffffffff816682db: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a08c0)
Location: security/security.c:3316
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff816a08c0-ffffffff816a092b: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_fix_setgid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd290)
Location: security/security.c:3388
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
```
**Symbols:**

```
ffffffff816dd290-ffffffff816dd2fb: security_task_fix_setgid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
