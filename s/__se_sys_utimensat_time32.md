# Function: <code>__se_sys_utimensat_time32</code>

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
In fs/utimes.c (ffffffff81306def)
Location: fs/utimes.c:243
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff81319e4f)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff81353dba)
Location: fs/utimes.c:243
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff813606aa)
Location: fs/utimes.c:250
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff8136717f)
Location: fs/utimes.c:251
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff813b5ccf)
Location: fs/utimes.c:251
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff8143b12f)
Location: fs/utimes.c:251
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff814c967f)
Location: fs/utimes.c:251
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff814ff8bf)
Location: fs/utimes.c:252
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff815344df)
Location: fs/utimes.c:252
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffff8000103d0eb0)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__arm64_sys_utimensat_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_utimensat_time32(long int dfd, long int filename, long int t, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c05ac1bc)
Location: fs/utimes.c:241
Inline: False
```
**Symbols:**

```
c05ac1bc-c05ac288: __se_sys_utimensat_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_utimensat_time32(long int dfd, long int filename, long int t, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d3a90)
Location: fs/utimes.c:241
Inline: False
```
**Symbols:**

```
c0000000004d3a90-c0000000004d3ba0: __se_sys_utimensat_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/utimes.c (ffffffff8131242f)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff8130303f)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff8131021f)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
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
In fs/utimes.c (ffffffff81321a1f)
Location: fs/utimes.c:241
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
