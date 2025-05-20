# Function: <code>__do_sys_userfaultfd</code>

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
In fs/userfaultfd.c (ffffffff812ef883)
Location: fs/userfaultfd.c:1901
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
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
In fs/userfaultfd.c (ffffffff81304203)
Location: fs/userfaultfd.c:1919
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813254c8)
Location: fs/userfaultfd.c:1939
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81338258)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_userfaultfd(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81372040)
Location: fs/userfaultfd.c:2004
Inline: False
Direct callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
**Symbols:**

```
ffffffff81372040-ffffffff81372146: __do_sys_userfaultfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __do_sys_userfaultfd(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:1964
Inline: False
Direct callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
**Symbols:**

```
ffffffff8137fe80-ffffffff8137ff96: __do_sys_userfaultfd (STB_LOCAL)
ffffffff81beac0a-ffffffff81beac26: __do_sys_userfaultfd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __do_sys_userfaultfd(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:2050
Inline: False
Direct callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
**Symbols:**

```
ffffffff81386b30-ffffffff81386c49: __do_sys_userfaultfd (STB_LOCAL)
ffffffff81bdcc37-ffffffff81bdcc53: __do_sys_userfaultfd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_userfaultfd(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:2062
Inline: False
Direct callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
**Symbols:**

```
ffffffff813d3e30-ffffffff813d3f57: __do_sys_userfaultfd (STB_LOCAL)
ffffffff81cc5656-ffffffff81cc5686: __do_sys_userfaultfd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_userfaultfd(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:2061
Inline: False
Direct callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
**Symbols:**

```
ffffffff8145d830-ffffffff8145d974: __do_sys_userfaultfd (STB_LOCAL)
ffffffff81e7804d-ffffffff81e78061: __do_sys_userfaultfd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ece70)
Location: fs/userfaultfd.c:2150
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff815240b0)
Location: fs/userfaultfd.c:2178
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81558640)
Location: fs/userfaultfd.c:2290
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f6d48)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
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
In fs/userfaultfd.c (c05cdc44)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
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
In fs/userfaultfd.c (c0000000004fe960)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
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
In fs/userfaultfd.c (ffffffe0002a8f10)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330838)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81321428)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8132e308)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81340c08)
Location: fs/userfaultfd.c:1945
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
