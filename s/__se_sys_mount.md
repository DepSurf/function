# Function: <code>__se_sys_mount</code>

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
In fs/namespace.c (ffffffff812c1bf5)
Location: fs/namespace.c:3109
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff812d6e95)
Location: fs/namespace.c:3081
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff812f52f5)
Location: fs/namespace.c:3340
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff81306e75)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff81340262)
Location: fs/namespace.c:3396
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff8134c285)
Location: fs/namespace.c:3418
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff81352e55)
Location: fs/namespace.c:3451
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff813a12a5)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff81424c34)
Location: fs/namespace.c:3568
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff814b1354)
Location: fs/namespace.c:3674
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff814e6394)
Location: fs/namespace.c:3861
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff8151a1d4)
Location: fs/namespace.c:3875
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffff8000103ba5b0)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_mount(long int dev_name, long int dir_name, long int type, long int flags, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0597f44)
Location: fs/namespace.c:3371
Inline: False
```
**Symbols:**

```
c0597f44-c0597f70: __se_sys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_mount(long int dev_name, long int dir_name, long int type, long int flags, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b7da0)
Location: fs/namespace.c:3371
Inline: False
```
**Symbols:**

```
c0000000004b7da0-c0000000004b7dd0: __se_sys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_mount(long int dev_name, long int dir_name, long int type, long int flags, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027c6c2)
Location: fs/namespace.c:3371
Inline: False
```
**Symbols:**

```
ffffffe00027c6c2-ffffffe00027c70c: __se_sys_mount (STB_GLOBAL)
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
In fs/namespace.c (ffffffff812ff455)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff812f0075)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff812fd245)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
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
In fs/namespace.c (ffffffff8130e5a5)
Location: fs/namespace.c:3371
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
