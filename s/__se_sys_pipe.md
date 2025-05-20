# Function: <code>__se_sys_pipe</code>

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
In fs/pipe.c (ffffffff812a4dc5)
Location: fs/pipe.c:871
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812b9e95)
Location: fs/pipe.c:864
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812d6b25)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812e8695)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff81320585)
Location: fs/pipe.c:1014
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff8132baf5)
Location: fs/pipe.c:1013
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff81331b25)
Location: fs/pipe.c:1027
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff8137f2a5)
Location: fs/pipe.c:1030
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff813ff325)
Location: fs/pipe.c:1031
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff814890b5)
Location: fs/pipe.c:1031
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff814bdfe5)
Location: fs/pipe.c:1036
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff814f0465)
Location: fs/pipe.c:1052
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffff800010391670)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__arm64_sys_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_pipe(long int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c057800c)
Location: fs/pipe.c:876
Inline: False
```
**Symbols:**

```
c057800c-c057802c: __se_sys_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_pipe(long int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0000000004896c0)
Location: fs/pipe.c:876
Inline: False
```
**Symbols:**

```
c0000000004896c0-c0000000004896f4: __se_sys_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_pipe(long int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe000260bfe)
Location: fs/pipe.c:876
Inline: False
```
**Symbols:**

```
ffffffe000260bfe-ffffffe000260c2a: __se_sys_pipe (STB_GLOBAL)
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
In fs/pipe.c (ffffffff812e0c75)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812d18b5)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812dea85)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
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
In fs/pipe.c (ffffffff812ef9f5)
Location: fs/pipe.c:876
Inline: True
Inline callers:
  - fs/pipe.c:__ia32_sys_pipe
  - fs/pipe.c:__x64_sys_pipe
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
