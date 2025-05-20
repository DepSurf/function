# Function: <code>pidfd_create</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf8e0)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810bf8e0-ffffffff810bf93d: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5cb0)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810c5cb0-ffffffff810c5d0d: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd748)
Location: kernel/pid.c:535
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8110)
Location: kernel/pid.c:556
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810c8110-ffffffff810c81b3: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9bb0)
Location: kernel/pid.c:556
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810c9bb0-ffffffff810c9c50: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd980)
Location: kernel/pid.c:558
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff810dd980-ffffffff810dda2f: pidfd_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7440)
Location: kernel/pid.c:594
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff810f7440-ffffffff810f7518: pidfd_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119bb0)
Location: kernel/pid.c:595
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff81119bb0-ffffffff81119c88: pidfd_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125e2c)
Location: kernel/pid.c:598
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff81127090-ffffffff811270f5: pidfd_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pidfd_create(struct pid *pid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8113042c)
Location: kernel/pid.c:598
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff81131670-ffffffff811316d5: pidfd_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff80001012438c)
Location: kernel/pid.c:470
Inline: True
Inline callers:
  - kernel/pid.c:__arm64_sys_pidfd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377d38)
Location: kernel/pid.c:470
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016dfc8)
Location: kernel/pid.c:470
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcd1a)
Location: kernel/pid.c:470
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
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
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0030)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810c0030-ffffffff810c008d: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae840)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810ae840-ffffffff810ae89d: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf580)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810bf580-ffffffff810bf5dd: pidfd_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pidfd_create(struct pid *pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7970)
Location: kernel/pid.c:470
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
```
**Symbols:**

```
ffffffff810c7970-ffffffff810c79cd: pidfd_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
