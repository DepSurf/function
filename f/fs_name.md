# Function: <code>fs_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b3f7)
Location: fs/filesystems.c:149
Inline: True
Inline callers:
  - fs/filesystems.c:SyS_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81253b57)
Location: fs/filesystems.c:149
Inline: True
Inline callers:
  - fs/filesystems.c:SyS_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266da7)
Location: fs/filesystems.c:149
Inline: True
Inline callers:
  - fs/filesystems.c:SyS_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812745e7)
Location: fs/filesystems.c:150
Inline: True
Inline callers:
  - fs/filesystems.c:SyS_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296ee7)
Location: fs/filesystems.c:151
Inline: True
Inline callers:
  - fs/filesystems.c:SyS_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bcf20)
Location: fs/filesystems.c:151
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812bcf20-ffffffff812bcfe3: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d21e0)
Location: fs/filesystems.c:151
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812d21e0-ffffffff812d22a3: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef240)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812ef240-ffffffff812ef303: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300d00)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff81300d00-ffffffff81300dda: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8133a0c0)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff8133a0c0-ffffffff8133a19a: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81345dd0)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff81345dd0-ffffffff81345eaa: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8134c190)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff8134c190-ffffffff8134c262: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81399fe0)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff81399fe0-ffffffff8139a0b2: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8141c8e0)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff8141c8e0-ffffffff8141c9c0: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814a8a30)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff814a8a30-ffffffff814a8b10: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814dda20)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff814dda20-ffffffff814ddb00: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81510470)
Location: fs/filesystems.c:156
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff81510470-ffffffff81510550: fs_name (STB_LOCAL)
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
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b3330)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__arm64_sys_sysfs
```
**Symbols:**

```
ffff8000103b3330-ffff8000103b359c: fs_name (STB_LOCAL)
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
In fs/filesystems.c (c0592214)
Location: fs/filesystems.c:155
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
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
In fs/filesystems.c (c0000000004aed00)
Location: fs/filesystems.c:155
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
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
In fs/filesystems.c (ffffffe000276e56)
Location: fs/filesystems.c:155
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
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
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f92e0)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812f92e0-ffffffff812f93ba: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812e9f00)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812e9f00-ffffffff812e9fda: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f70d0)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff812f70d0-ffffffff812f71aa: fs_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fs_name(unsigned int index, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff813083e0)
Location: fs/filesystems.c:155
Inline: False
Direct callers:
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
```
**Symbols:**

```
ffffffff813083e0-ffffffff813084c2: fs_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
