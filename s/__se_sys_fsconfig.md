# Function: <code>__se_sys_fsconfig</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffff8130b8d1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff8131e8e1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81358cb5)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81365635)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff8136c085)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff813bad55)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81440b25)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff814cfa15)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81505cd5)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff8153aa35)
Location: fs/fsopen.c:349
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffff8000103d6ae8)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_fsconfig(long int fd, long int cmd, long int _key, long int _value, long int aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (c05b0abc)
Location: fs/fsopen.c:314
Inline: False
```
**Symbols:**

```
c05b0abc-c05b0fb0: __se_sys_fsconfig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_fsconfig(long int fd, long int cmd, long int _key, long int _value, long int aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (c0000000004dae70)
Location: fs/fsopen.c:314
Inline: False
```
**Symbols:**

```
c0000000004dae70-c0000000004db50c: __se_sys_fsconfig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_fsconfig(long int fd, long int cmd, long int _key, long int _value, long int aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fsopen.c (ffffffe0002909ec)
Location: fs/fsopen.c:314
Inline: False
```
**Symbols:**

```
ffffffe0002909ec-ffffffe000290ddc: __se_sys_fsconfig (STB_GLOBAL)
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
In fs/fsopen.c (ffffffff81316ec1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81307ab1)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81314991)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81326501)
Location: fs/fsopen.c:314
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
