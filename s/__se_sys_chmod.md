# Function: <code>__se_sys_chmod</code>

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
In fs/open.c (ffffffff812966c5)
Location: fs/open.c:610
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812ab4b5)
Location: fs/open.c:599
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812c7cb5)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812d96c5)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f485)
Location: fs/open.c:648
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b375)
Location: fs/open.c:638
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321485)
Location: fs/open.c:640
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e965)
Location: fs/open.c:637
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ed155)
Location: fs/open.c:661
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff81475785)
Location: fs/open.c:661
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff814aa115)
Location: fs/open.c:698
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff814db5a7)
Location: fs/open.c:718
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffff80001037ea30)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_chmod(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569398)
Location: fs/open.c:619
Inline: False
```
**Symbols:**

```
c0569398-c05693c0: __se_sys_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_chmod(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474680)
Location: fs/open.c:619
Inline: False
```
**Symbols:**

```
c000000000474680-c0000000004746c0: __se_sys_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_chmod(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254690)
Location: fs/open.c:619
Inline: False
```
**Symbols:**

```
ffffffe000254690-ffffffe0002546ca: __se_sys_chmod (STB_GLOBAL)
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
In fs/open.c (ffffffff812d1ca5)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812c2925)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812cfab5)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
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
In fs/open.c (ffffffff812e08c5)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
