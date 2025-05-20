# Function: <code>security_getprocattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133efd0)
Location: security/security.c:1133
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff8133efd0-ffffffff8133f025: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813745f0)
Location: security/security.c:1157
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff813745f0-ffffffff81374645: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138af20)
Location: security/security.c:1178
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff8138af20-ffffffff8138af75: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0620)
Location: security/security.c:1926
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff813a0620-ffffffff813a0866: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c63d0)
Location: security/security.c:1900
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff813c63d0-ffffffff813c64d1: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5fb0)
Location: security/security.c:1282
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff813f5fb0-ffffffff813f6001: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411760)
Location: security/security.c:1926
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff81411760-ffffffff8141186e: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eff0)
Location: security/security.c:1945
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff8143eff0-ffffffff8143f104: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814589a0)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814589a0-ffffffff81458ab6: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab8d0)
Location: security/security.c:2186
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814ab8d0-ffffffff814abaff: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8ed0)
Location: security/security.c:2203
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814c8ed0-ffffffff814c90ff: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf510)
Location: security/security.c:2266
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814cf510-ffffffff814cf730: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815281d0)
Location: security/security.c:2274
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff815281d0-ffffffff81528416: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd2c0)
Location: security/security.c:2285
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff815bd2c0-ffffffff815bd568: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, int lsmid, const char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669660)
Location: security/security.c:2361
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff81669660-ffffffff81669703: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, int lsmid, const char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1c60)
Location: security/security.c:4006
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff816a1c60-ffffffff816a1cfe: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, int lsmid, const char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de830)
Location: security/security.c:4185
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff816de830-ffffffff816de89c: security_getprocattr (STB_GLOBAL)
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
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105448f0)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffff8000105448f0-ffff800010544a00: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa7c4)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
c06fa7c4-c06fa8dc: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006999d0)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
c0000000006999d0-c000000000699f8c: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0972)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffe0003a0972-ffffffe0003a0a50: security_getprocattr (STB_GLOBAL)
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
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450f80)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff81450f80-ffffffff81451096: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814419d0)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814419d0-ffffffff81441ae6: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d020)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff8144d020-ffffffff8144d136: security_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_getprocattr(struct task_struct *p, const char *lsm, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814643f0)
Location: security/security.c:1984
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_read
```
**Symbols:**

```
ffffffff814643f0-ffffffff81464506: security_getprocattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, name, value</code> ➡️ <code>p, lsm, name, value</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, lsm, name, value</code> ➡️ <code>p, name, value</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, name, value</code> ➡️ <code>p, lsm, name, value</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int lsmid</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *name</code> ➡️ <code>const char *name</code>
</li>
</ul>
</details>
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
