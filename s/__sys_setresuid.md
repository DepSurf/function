# Function: <code>__sys_setresuid</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a6df0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810a6df0-ffffffff810a6fb0: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810afb00)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810afb00-ffffffff810afcc0: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b54b0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810b54b0-ffffffff810b5670: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bbaa0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810bbaa0-ffffffff810bbc60: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c3400)
Location: kernel/sys.c:630
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810c3400-ffffffff810c35ca: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be810)
Location: kernel/sys.c:631
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810be810-ffffffff810be9da: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0170)
Location: kernel/sys.c:644
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810c0170-ffffffff810c0346: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d2c30)
Location: kernel/sys.c:652
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810d2c30-ffffffff810d2e40: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ebe80)
Location: kernel/sys.c:659
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810ebe80-ffffffff810ec2a5: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110d140)
Location: kernel/sys.c:660
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff8110d140-ffffffff8110d565: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811192d0)
Location: kernel/sys.c:667
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff811192d0-ffffffff81119713: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81122cc0)
Location: kernel/sys.c:667
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff81122cc0-ffffffff81123103: __sys_setresuid (STB_GLOBAL)
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
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101184c0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setresuid
  - kernel/uid16.c:__arm64_sys_setresuid16
```
**Symbols:**

```
ffff8000101184c0-ffff8000101186e0: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036c48c)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setresuid
  - kernel/uid16.c:__se_sys_setresuid16
```
**Symbols:**

```
c036c48c-c036c68c: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015fdc0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setresuid
```
**Symbols:**

```
c00000000015fdc0-c000000000160060: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d33f4)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setresuid
```
**Symbols:**

```
ffffffe0000d33f4-ffffffe0000d3594: __sys_setresuid (STB_GLOBAL)
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
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5e10)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810b5e10-ffffffff810b5fd0: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4750)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810a4750-ffffffff810a4910: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5370)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810b5370-ffffffff810b5530: __sys_setresuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_setresuid(uid_t ruid, uid_t euid, uid_t suid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd6e0)
Location: kernel/sys.c:621
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setresuid
  - kernel/sys.c:__x64_sys_setresuid
  - kernel/uid16.c:__ia32_sys_setresuid16
  - kernel/uid16.c:__x64_sys_setresuid16
```
**Symbols:**

```
ffffffff810bd6e0-ffffffff810bd8a0: __sys_setresuid (STB_GLOBAL)
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
