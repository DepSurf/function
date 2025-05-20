# Function: <code>security_setprocattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_setprocattr(struct task_struct *p, char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133f030)
Location: security/security.c:1138
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff8133f030-ffffffff8133f08f: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_setprocattr(struct task_struct *p, char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374650)
Location: security/security.c:1162
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81374650-ffffffff813746af: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_setprocattr(struct task_struct *p, char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138af80)
Location: security/security.c:1183
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff8138af80-ffffffff8138afdf: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0870)
Location: security/security.c:1995
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff813a0870-ffffffff813a0b9b: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c64e0)
Location: security/security.c:1930
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff813c64e0-ffffffff813c65c4: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_setprocattr(const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6010)
Location: security/security.c:1287
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff813f6010-ffffffff813f6061: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411870)
Location: security/security.c:1957
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81411870-ffffffff81411ac8: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f110)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff8143f110-ffffffff8143f35e: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458ac0)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81458ac0-ffffffff81458d19: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814abb00)
Location: security/security.c:2270
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff814abb00-ffffffff814abcbb: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9100)
Location: security/security.c:2287
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff814c9100-ffffffff814c92bb: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf730)
Location: security/security.c:2350
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff814cf730-ffffffff814cf8e9: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528420)
Location: security/security.c:2358
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81528420-ffffffff81528619: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd570)
Location: security/security.c:2369
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff815bd570-ffffffff815bd7c6: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_setprocattr(int lsmid, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669720)
Location: security/security.c:2393
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81669720-ffffffff816697c1: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_setprocattr(int lsmid, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1d10)
Location: security/security.c:4038
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff816a1d10-ffffffff816a1dac: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_setprocattr(int lsmid, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de8b0)
Location: security/security.c:4209
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff816de8b0-ffffffff816de920: security_setprocattr (STB_GLOBAL)
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
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544a00)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffff800010544a00-ffff800010544c3c: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa8dc)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
c06fa8dc-c06fab60: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699f90)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
c000000000699f90-c00000000069a704: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0a50)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffe0003a0a50-ffffffe0003a0c36: security_setprocattr (STB_GLOBAL)
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
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814510a0)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff814510a0-ffffffff814512f9: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441af0)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81441af0-ffffffff81441d49: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d140)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff8144d140-ffffffff8144d399: security_setprocattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_setprocattr(const char *lsm, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464510)
Location: security/security.c:2015
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_attr_write
```
**Symbols:**

```
ffffffff81464510-ffffffff81464769: security_setprocattr (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct task_struct *p</code>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *lsm</code>
</li>
<li>
<b>Param reordered. </b>
<code>lsm, name, value, size</code> ➡️ <code>name, value, size</code>
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
<code>name, value, size</code> ➡️ <code>lsm, name, value, size</code>
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
