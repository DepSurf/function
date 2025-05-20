# Function: <code>__do_compat_sys_socketcall</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c9fcb)
Location: net/compat.c:844
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f4feb)
Location: net/compat.c:838
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953e70)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81953e70-ffffffff819541c3: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8198a3c0)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8198a3c0-ffffffff8198a6ed: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a62750)
Location: net/compat.c:544
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a62750-ffffffff81a62a7d: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a6a870)
Location: net/compat.c:424
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a6a870-ffffffff81a6ab9d: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a52fa0)
Location: net/compat.c:424
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a52fa0-ffffffff81a532cd: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81b0bc70)
Location: net/compat.c:424
Inline: False
Direct callers:
  - net/compat.c:__x64_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81b0bc70-ffffffff81b0bfd5: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81c923a0)
Location: net/compat.c:424
Inline: False
Direct callers:
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81c923a0-ffffffff81c9270c: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81e4da10)
Location: net/compat.c:422
Inline: False
Direct callers:
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e4da10-ffffffff81e4dd7c: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81ea9060)
Location: net/compat.c:423
Inline: False
Direct callers:
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ea9060-ffffffff81ea9406: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81f6bb20)
Location: net/compat.c:423
Inline: False
Direct callers:
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81f6bb20-ffffffff81f6bec6: __do_compat_sys_socketcall (STB_LOCAL)
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
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c32e78)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__arm64_compat_sys_socketcall
```
**Symbols:**

```
ffff800010c32e78-ffff800010c33264: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2bea0)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__se_compat_sys_socketcall
```
**Symbols:**

```
c000000000d2bea0-c000000000d2c2f4: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8192a230)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8192a230-ffffffff8192a55d: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e3fe0)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818e3fe0-ffffffff818e430d: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197b3c0)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8197b3c0-ffffffff8197b6ed: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d910)
Location: net/compat.c:719
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8199d910-ffffffff8199dc3d: __do_compat_sys_socketcall (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
