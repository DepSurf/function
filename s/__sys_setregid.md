# Function: <code>__sys_setregid</code>

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
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a67d0)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810a67d0-ffffffff810a693f: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810af4e0)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810af4e0-ffffffff810af64f: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b4e50)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810b4e50-ffffffff810b4fc7: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bb440)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810bb440-ffffffff810bb5b7: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c2d90)
Location: kernel/sys.c:351
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810c2d90-ffffffff810c2f3a: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be1a0)
Location: kernel/sys.c:352
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810be1a0-ffffffff810be34a: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bfae0)
Location: kernel/sys.c:357
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810bfae0-ffffffff810bfc8a: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d2550)
Location: kernel/sys.c:357
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810d2550-ffffffff810d26fa: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810eb630)
Location: kernel/sys.c:364
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810eb630-ffffffff810eb7df: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110c830)
Location: kernel/sys.c:365
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff8110c830-ffffffff8110c9df: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811189f0)
Location: kernel/sys.c:372
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff811189f0-ffffffff81118b9f: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811223e0)
Location: kernel/sys.c:372
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff811223e0-ffffffff8112258f: __sys_setregid (STB_GLOBAL)
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
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010117e98)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setregid
  - kernel/uid16.c:__arm64_sys_setregid16
```
**Symbols:**

```
ffff800010117e98-ffff800010118020: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036bed4)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setregid
  - kernel/uid16.c:__se_sys_setregid16
```
**Symbols:**

```
c036bed4-c036c058: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015f660)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setregid
```
**Symbols:**

```
c00000000015f660-c00000000015f828: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d2ed6)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setregid
```
**Symbols:**

```
ffffffe0000d2ed6-ffffffe0000d300c: __sys_setregid (STB_GLOBAL)
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
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b57b0)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810b57b0-ffffffff810b5927: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a40f0)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810a40f0-ffffffff810a4267: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b4d10)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810b4d10-ffffffff810b4e87: __sys_setregid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_setregid(gid_t rgid, gid_t egid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd080)
Location: kernel/sys.c:350
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setregid
  - kernel/sys.c:__x64_sys_setregid
  - kernel/uid16.c:__ia32_sys_setregid16
  - kernel/uid16.c:__x64_sys_setregid16
```
**Symbols:**

```
ffffffff810bd080-ffffffff810bd1f7: __sys_setregid (STB_GLOBAL)
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
