# Function: <code>apparmor_getprocattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81384440)
Location: security/apparmor/lsm.c:593
Inline: False
```
**Symbols:**

```
ffffffff81384440-ffffffff81384787: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813bedd0)
Location: security/apparmor/lsm.c:567
Inline: False
```
**Symbols:**

```
ffffffff813bedd0-ffffffff813bf121: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d6250)
Location: security/apparmor/lsm.c:570
Inline: False
```
**Symbols:**

```
ffffffff813d6250-ffffffff813d65a1: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e9f70)
Location: security/apparmor/lsm.c:553
Inline: False
```
**Symbols:**

```
ffffffff813e9f70-ffffffff813ea1bb: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814115e0)
Location: security/apparmor/lsm.c:553
Inline: False
```
**Symbols:**

```
ffffffff814115e0-ffffffff8141180f: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81443d60)
Location: security/apparmor/lsm.c:582
Inline: False
```
**Symbols:**

```
ffffffff81443d60-ffffffff81443fae: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145f490)
Location: security/apparmor/lsm.c:577
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff8145f490-ffffffff8145f704: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148c8c0)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff8148c8c0-ffffffff8148cad7: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a6780)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff814a6780-ffffffff814a6997: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81503e30)
Location: security/apparmor/lsm.c:589
Inline: False
```
**Symbols:**

```
ffffffff81503e30-ffffffff81504183: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81521230)
Location: security/apparmor/lsm.c:589
Inline: False
```
**Symbols:**

```
ffffffff81521230-ffffffff81521588: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81527660)
Location: security/apparmor/lsm.c:598
Inline: False
```
**Symbols:**

```
ffffffff81527660-ffffffff81527973: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815858f0)
Location: security/apparmor/lsm.c:598
Inline: False
```
**Symbols:**

```
ffffffff815858f0-ffffffff81585c03: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81626400)
Location: security/apparmor/lsm.c:791
Inline: False
```
**Symbols:**

```
ffffffff81626400-ffffffff8162676a: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, const char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d8b40)
Location: security/apparmor/lsm.c:837
Inline: False
```
**Symbols:**

```
ffffffff816d8b40-ffffffff816d8db5: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, const char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81711c60)
Location: security/apparmor/lsm.c:985
Inline: False
```
**Symbols:**

```
ffffffff81711c60-ffffffff81711ed6: apparmor_getprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, const char *name, char **value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff817512f0)
Location: security/apparmor/lsm.c:1024
Inline: False
```
**Symbols:**

```
ffffffff817512f0-ffffffff8175156f: apparmor_getprocattr (STB_LOCAL)
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
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059d890)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffff80001059d890-ffff80001059da98: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074e2e4)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
c074e2e4-c074e4d8: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000715a70)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
c000000000715a70-c00000000071613c: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e9c02)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffe0003e9c02-ffffffe0003e9daa: apparmor_getprocattr (STB_GLOBAL)
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
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149ed60)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff8149ed60-ffffffff8149ef77: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148f780)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff8148f780-ffffffff8148f997: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149ae00)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff8149ae00-ffffffff8149b017: apparmor_getprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apparmor_getprocattr(struct task_struct *task, char *name, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b31a0)
Location: security/apparmor/lsm.c:573
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_read
```
**Symbols:**

```
ffffffff814b31a0-ffffffff814b33d6: apparmor_getprocattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
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
