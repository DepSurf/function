# Function: <code>__se_sys_chdir</code>

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
In fs/open.c (ffffffff81296375)
Location: fs/open.c:474
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812ab165)
Location: fs/open.c:463
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812c7965)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812d9375)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff8130f135)
Location: fs/open.c:512
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff813199f0)
Location: fs/open.c:486
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff8131fdd0)
Location: fs/open.c:487
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff8136d370)
Location: fs/open.c:484
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff813eb750)
Location: fs/open.c:508
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff81473ae0)
Location: fs/open.c:508
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff814a82d0)
Location: fs/open.c:545
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff814d9370)
Location: fs/open.c:550
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffff80001037e6f0)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_chdir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_chdir(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569010)
Location: fs/open.c:483
Inline: False
```
**Symbols:**

```
c0569010-c056902c: __se_sys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_chdir(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474260)
Location: fs/open.c:483
Inline: False
```
**Symbols:**

```
c000000000474260-c000000000474290: __se_sys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_chdir(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe00025432e)
Location: fs/open.c:483
Inline: False
```
**Symbols:**

```
ffffffe00025432e-ffffffe000254358: __se_sys_chdir (STB_GLOBAL)
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
In fs/open.c (ffffffff812d1955)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812c25d5)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812cf765)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
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
In fs/open.c (ffffffff812e0575)
Location: fs/open.c:483
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
