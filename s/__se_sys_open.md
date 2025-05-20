# Function: <code>__se_sys_open</code>

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
In fs/open.c (ffffffff81296fa5)
Location: fs/open.c:1120
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812abc55)
Location: fs/open.c:1087
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812c8465)
Location: fs/open.c:1107
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812d9e75)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff81310065)
Location: fs/open.c:1200
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff8131c325)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff81322495)
Location: fs/open.c:1215
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff8136f985)
Location: fs/open.c:1233
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff813ee2b5)
Location: fs/open.c:1298
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff81476b65)
Location: fs/open.c:1330
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff814ab433)
Location: fs/open.c:1426
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff814dc8d3)
Location: fs/open.c:1423
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffff80001037f208)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_open(long int filename, long int flags, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569ad4)
Location: fs/open.c:1112
Inline: False
```
**Symbols:**

```
c0569ad4-c0569b04: __se_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_open(long int filename, long int flags, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000475190)
Location: fs/open.c:1112
Inline: False
```
**Symbols:**

```
c000000000475190-c0000000004751bc: __se_sys_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_open(long int filename, long int flags, long int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254d84)
Location: fs/open.c:1112
Inline: False
```
**Symbols:**

```
ffffffe000254d84-ffffffe000254dcc: __se_sys_open (STB_GLOBAL)
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
In fs/open.c (ffffffff812d2455)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812c30d5)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812d0265)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In fs/open.c (ffffffff812e1095)
Location: fs/open.c:1112
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
