# Function: <code>__se_sys_access</code>

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
In fs/open.c (ffffffff81296265)
Location: fs/open.c:443
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812ab055)
Location: fs/open.c:432
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812c7855)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812d9265)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff8130f025)
Location: fs/open.c:481
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff813199a5)
Location: fs/open.c:481
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff8131fa65)
Location: fs/open.c:482
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff8136d005)
Location: fs/open.c:479
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff813eb355)
Location: fs/open.c:503
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff81473605)
Location: fs/open.c:503
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff814a7df5)
Location: fs/open.c:540
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff814d90a5)
Location: fs/open.c:545
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffff80001037e5e8)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_access
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_access(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568f08)
Location: fs/open.c:452
Inline: False
```
**Symbols:**

```
c0568f08-c0568f30: __se_sys_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_access(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474130)
Location: fs/open.c:452
Inline: False
```
**Symbols:**

```
c000000000474130-c000000000474154: __se_sys_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_access(long int filename, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254254)
Location: fs/open.c:452
Inline: False
```
**Symbols:**

```
ffffffe000254254-ffffffe00025428c: __se_sys_access (STB_GLOBAL)
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
In fs/open.c (ffffffff812d1845)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812c24c5)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812cf655)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
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
In fs/open.c (ffffffff812e0465)
Location: fs/open.c:452
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
