# Function: <code>apparmor_setprocattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apparmor_setprocattr(struct task_struct *task, char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81383c30)
Location: security/apparmor/lsm.c:620
Inline: False
```
**Symbols:**

```
ffffffff81383c30-ffffffff8138406b: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apparmor_setprocattr(struct task_struct *task, char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813be430)
Location: security/apparmor/lsm.c:594
Inline: False
```
**Symbols:**

```
ffffffff813be430-ffffffff813be90a: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apparmor_setprocattr(struct task_struct *task, char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d58b0)
Location: security/apparmor/lsm.c:597
Inline: False
```
**Symbols:**

```
ffffffff813d58b0-ffffffff813d5d8a: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e9460)
Location: security/apparmor/lsm.c:605
Inline: False
```
**Symbols:**

```
ffffffff813e9460-ffffffff813e9836: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81410600)
Location: security/apparmor/lsm.c:580
Inline: False
```
**Symbols:**

```
ffffffff81410600-ffffffff81410a23: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81442370)
Location: security/apparmor/lsm.c:609
Inline: False
```
**Symbols:**

```
ffffffff81442370-ffffffff814427b6: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145fad0)
Location: security/apparmor/lsm.c:603
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff8145fad0-ffffffff8145ff3a: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148df10)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff8148df10-ffffffff8148e352: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a7dd0)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff814a7dd0-ffffffff814a8212: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815033e0)
Location: security/apparmor/lsm.c:639
Inline: False
```
**Symbols:**

```
ffffffff815033e0-ffffffff8150390b: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81521f00)
Location: security/apparmor/lsm.c:639
Inline: False
```
**Symbols:**

```
ffffffff81521f00-ffffffff8152242b: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815282c0)
Location: security/apparmor/lsm.c:648
Inline: False
```
**Symbols:**

```
ffffffff815282c0-ffffffff815287c2: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81586550)
Location: security/apparmor/lsm.c:648
Inline: False
```
**Symbols:**

```
ffffffff81586550-ffffffff81586a52: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81626870)
Location: security/apparmor/lsm.c:843
Inline: False
```
**Symbols:**

```
ffffffff81626870-ffffffff81626de7: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d5ac0)
Location: security/apparmor/lsm.c:906
Inline: False
```
**Symbols:**

```
ffffffff816d5ac0-ffffffff816d5e37: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8170ecc0)
Location: security/apparmor/lsm.c:1054
Inline: False
```
**Symbols:**

```
ffffffff8170ecc0-ffffffff8170f056: apparmor_setprocattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8174d350)
Location: security/apparmor/lsm.c:1143
Inline: False
```
**Symbols:**

```
ffffffff8174d350-ffffffff8174d38f: apparmor_setprocattr (STB_LOCAL)
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
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059ce90)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffff80001059ce90-ffff80001059d23c: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074ca1c)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
c074ca1c-c074ce0c: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000717360)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
c000000000717360-c00000000071830c: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e8158)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffe0003e8158-ffffffe0003e84a8: apparmor_setprocattr (STB_GLOBAL)
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
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a03b0)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff814a03b0-ffffffff814a07f2: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81490dd0)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff81490dd0-ffffffff81491212: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149c450)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff8149c450-ffffffff8149c892: apparmor_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apparmor_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b49d0)
Location: security/apparmor/lsm.c:599
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:attr_write
```
**Symbols:**

```
ffffffff814b49d0-ffffffff814b4e1d: apparmor_setprocattr (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, name, value, size</code> ➡️ <code>name, value, size</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *name</code> ➡️ <code>const char *name</code>
</li>
</ul>
</details>
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
