# Function: <code>__sys_setfsgid</code>

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
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a72d0)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810a72d0-ffffffff810a738c: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810affe0)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810affe0-ffffffff810b009c: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b59a0)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810b59a0-ffffffff810b5a62: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bbf90)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810bbf90-ffffffff810bc052: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c3920)
Location: kernel/sys.c:854
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810c3920-ffffffff810c39f4: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bed20)
Location: kernel/sys.c:855
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810bed20-ffffffff810bedee: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c06a0)
Location: kernel/sys.c:872
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810c06a0-ffffffff810c0771: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d3190)
Location: kernel/sys.c:881
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810d3190-ffffffff810d3261: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ec7c0)
Location: kernel/sys.c:888
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810ec7c0-ffffffff810ec88e: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110db10)
Location: kernel/sys.c:889
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff8110db10-ffffffff8110dbde: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81119da0)
Location: kernel/sys.c:907
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff81119da0-ffffffff81119e6e: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81123790)
Location: kernel/sys.c:907
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff81123790-ffffffff8112385e: __sys_setfsgid (STB_GLOBAL)
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
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010118a20)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_setfsgid
  - kernel/uid16.c:__arm64_sys_setfsgid16
```
**Symbols:**

```
ffff800010118a20-ffff800010118b04: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036cbbc)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setfsgid
  - kernel/uid16.c:__se_sys_setfsgid16
```
**Symbols:**

```
c036cbbc-c036cc90: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000000160430)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setfsgid
```
**Symbols:**

```
c000000000160430-c0000000001605a4: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d3a2a)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_setfsgid
```
**Symbols:**

```
ffffffe0000d3a2a-ffffffe0000d3af8: __sys_setfsgid (STB_GLOBAL)
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
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6300)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810b6300-ffffffff810b63c2: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4c40)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810a4c40-ffffffff810a4d02: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b5860)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810b5860-ffffffff810b5922: __sys_setfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_setfsgid(gid_t gid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bdbd0)
Location: kernel/sys.c:841
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setfsgid
  - kernel/sys.c:__x64_sys_setfsgid
  - kernel/uid16.c:__ia32_sys_setfsgid16
  - kernel/uid16.c:__x64_sys_setfsgid16
```
**Symbols:**

```
ffffffff810bdbd0-ffffffff810bdc92: __sys_setfsgid (STB_GLOBAL)
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
