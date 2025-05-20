# Function: <code>__se_sys_bdflush</code>

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
In fs/buffer.c (ffffffff812d6805)
Location: fs/buffer.c:3294
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff812ebc85)
Location: fs/buffer.c:3306
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff8130d3a5)
Location: fs/buffer.c:3313
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff81320375)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff81359555)
Location: fs/buffer.c:3300
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff81367315)
Location: fs/buffer.c:3281
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff8136dd15)
Location: fs/buffer.c:3302
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/buffer.c (ffff8000103d7a08)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__arm64_sys_bdflush
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_bdflush(long int func, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b75e0)
Location: fs/buffer.c:3290
Inline: False
```
**Symbols:**

```
c05b75e0-c05b766c: __se_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_bdflush(long int func, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dce70)
Location: fs/buffer.c:3290
Inline: False
```
**Symbols:**

```
c0000000004dce70-c0000000004dcf28: __se_sys_bdflush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_bdflush(long int func, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000296038)
Location: fs/buffer.c:3290
Inline: False
```
**Symbols:**

```
ffffffe000296038-ffffffe0002960b4: __se_sys_bdflush (STB_GLOBAL)
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
In fs/buffer.c (ffffffff81318955)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff81309545)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff81316425)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
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
In fs/buffer.c (ffffffff813281e5)
Location: fs/buffer.c:3290
Inline: True
Inline callers:
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
