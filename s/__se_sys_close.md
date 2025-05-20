# Function: <code>__se_sys_close</code>

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
In fs/open.c (ffffffff81294b25)
Location: fs/open.c:1201
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812a95d5)
Location: fs/open.c:1168
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812c5d45)
Location: fs/open.c:1188
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812d7755)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff8130df75)
Location: fs/open.c:1300
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff81319d05)
Location: fs/open.c:1298
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff8131fb15)
Location: fs/open.c:1320
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff8136d0b5)
Location: fs/open.c:1338
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff813eb835)
Location: fs/open.c:1405
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff81473725)
Location: fs/open.c:1438
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff814a7f25)
Location: fs/open.c:1534
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff814d9465)
Location: fs/open.c:1539
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffff80001037cb70)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_close
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_close(long int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569b50)
Location: fs/open.c:1193
Inline: False
```
**Symbols:**

```
c0569b50-c0569ba8: __se_sys_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_close(long int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000471e90)
Location: fs/open.c:1193
Inline: False
```
**Symbols:**

```
c000000000471e90-c000000000471f04: __se_sys_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_close(long int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254e58)
Location: fs/open.c:1193
Inline: False
```
**Symbols:**

```
ffffffe000254e58-ffffffe000254eac: __se_sys_close (STB_GLOBAL)
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
In fs/open.c (ffffffff812cfd35)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812c09b5)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812cdb45)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
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
In fs/open.c (ffffffff812de955)
Location: fs/open.c:1193
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
