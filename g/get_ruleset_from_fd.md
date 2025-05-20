# Function: <code>get_ruleset_from_fd</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81537260)
Location: security/landlock/syscalls.c:206
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff81537260-ffffffff8153734a: get_ruleset_from_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff815959e0)
Location: security/landlock/syscalls.c:206
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff815959e0-ffffffff81595aca: get_ruleset_from_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81637cb0)
Location: security/landlock/syscalls.c:208
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff81637cb0-ffffffff81637da0: get_ruleset_from_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff816ef0b0)
Location: security/landlock/syscalls.c:208
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff816ef0b0-ffffffff816ef1a0: get_ruleset_from_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81729550)
Location: security/landlock/syscalls.c:208
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff81729550-ffffffff81729643: get_ruleset_from_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct landlock_ruleset *get_ruleset_from_fd(const int fd, const fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff8176aba0)
Location: security/landlock/syscalls.c:222
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__x64_sys_landlock_restrict_self
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff8176aba0-ffffffff8176ac93: get_ruleset_from_fd (STB_LOCAL)
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
