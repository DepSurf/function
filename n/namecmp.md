# Function: <code>namecmp</code>

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
In fs/proc/proc_sysctl.c (ffffffff812844f0)
Location: fs/proc/proc_sysctl.c:86
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812b271a)
Location: fs/proc/proc_sysctl.c:86
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
In fs/proc/proc_sysctl.c (ffffffff812c7f6a)
Location: fs/proc/proc_sysctl.c:86
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d3bf0)
Location: fs/proc/proc_sysctl.c:87
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812d3bf0-ffffffff812d3c20: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8420)
Location: fs/proc/proc_sysctl.c:88
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff812f8420-ffffffff812f8450: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813256d0)
Location: fs/proc/proc_sysctl.c:88
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813256d0-ffffffff81325700: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133c870)
Location: fs/proc/proc_sysctl.c:88
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8133c870-ffffffff8133c8a0: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81364ab0)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81364ab0-ffffffff81364ae0: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137cd40)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff8137cd40-ffffffff8137cd70: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c6820)
Location: fs/proc/proc_sysctl.c:94
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff813c6820-ffffffff813c6850: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d87c0)
Location: fs/proc/proc_sysctl.c:95
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff813d87c0-ffffffff813d87f0: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813df690)
Location: fs/proc/proc_sysctl.c:95
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff813df690-ffffffff813df6c0: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81431040)
Location: fs/proc/proc_sysctl.c:95
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff81431040-ffffffff81431070: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814aade0)
Location: fs/proc/proc_sysctl.c:116
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff814aade0-ffffffff814aae1c: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81540c40)
Location: fs/proc/proc_sysctl.c:109
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff81540c40-ffffffff81540c7c: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81578ff0)
Location: fs/proc/proc_sysctl.c:101
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff81578ff0-ffffffff8157902c: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b17c0)
Location: fs/proc/proc_sysctl.c:101
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
**Symbols:**

```
ffffffff815b17c0-ffffffff815b17fc: namecmp (STB_LOCAL)
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
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff8000104496d8)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffff8000104496d8-ffff800010449730: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060e7e4)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:find_entry
```
**Symbols:**

```
c060e7e4-c060e820: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0000000005603d0)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
c0000000005603d0-c000000000560444: namecmp (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffe0002e00c8)
Location: fs/proc/proc_sysctl.c:93
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
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
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375320)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81375320-ffffffff81375350: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365df0)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81365df0-ffffffff81365e20: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81372df0)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff81372df0-ffffffff81372e20: namecmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int namecmp(const char *name1, int len1, const char *name2, int len2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813867c0)
Location: fs/proc/proc_sysctl.c:93
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:insert_header
```
**Symbols:**

```
ffffffff813867c0-ffffffff813867f0: namecmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
