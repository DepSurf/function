# Function: <code>security_task_setpgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e4b0)
Location: security/security.c:929
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff8133e4b0-ffffffff8133e4ff: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373ac0)
Location: security/security.c:953
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff81373ac0-ffffffff81373b0f: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a3f0)
Location: security/security.c:974
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff8138a3f0-ffffffff8138a43f: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f8e0)
Location: security/security.c:1611
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff8139f8e0-ffffffff8139f92f: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c54d0)
Location: security/security.c:1573
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff813c54d0-ffffffff813c5525: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5580)
Location: security/security.c:1077
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff813f5580-ffffffff813f55c4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410bb0)
Location: security/security.c:1685
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff81410bb0-ffffffff81410bf4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e370)
Location: security/security.c:1704
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff8143e370-ffffffff8143e3bd: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457df0)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff81457df0-ffffffff81457e34: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aac80)
Location: security/security.c:1933
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff814aac80-ffffffff814aacc4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8280)
Location: security/security.c:1950
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff814c8280-ffffffff814c82c4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce8c0)
Location: security/security.c:2000
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff814ce8c0-ffffffff814ce904: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527580)
Location: security/security.c:2008
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff81527580-ffffffff815275c4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc380)
Location: security/security.c:2013
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff815bc380-ffffffff815bc3dd: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668360)
Location: security/security.c:2065
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff81668360-ffffffff816683bd: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a09b0)
Location: security/security.c:3349
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff816a09b0-ffffffff816a0a0d: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd380)
Location: security/security.c:3421
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff816dd380-ffffffff816dd3dd: security_task_setpgid (STB_GLOBAL)
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
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543b18)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setpgid
```
**Symbols:**

```
ffff800010543b18-ffff800010543b78: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9a6c)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setpgid
```
**Symbols:**

```
c06f9a6c-c06f9ac8: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697fb0)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setpgid
```
**Symbols:**

```
c000000000697fb0-c00000000069806c: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ff1c)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setpgid
```
**Symbols:**

```
ffffffe00039ff1c-ffffffe00039ff60: security_task_setpgid (STB_GLOBAL)
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
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814503d0)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff814503d0-ffffffff81450414: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440e20)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff81440e20-ffffffff81440e64: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c470)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff8144c470-ffffffff8144c4b4: security_task_setpgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_setpgid(struct task_struct *p, pid_t pgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463840)
Location: security/security.c:1743
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff81463840-ffffffff81463884: security_task_setpgid (STB_GLOBAL)
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
