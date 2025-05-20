# Function: <code>__se_sys_utime32</code>

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
In fs/utimes.c (ffffffff81306d47)
Location: fs/utimes.c:227
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81319da7)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81353d12)
Location: fs/utimes.c:227
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81360602)
Location: fs/utimes.c:234
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff813670d7)
Location: fs/utimes.c:235
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff813b5c27)
Location: fs/utimes.c:235
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff8143b067)
Location: fs/utimes.c:235
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff814c95a7)
Location: fs/utimes.c:235
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff814ff7e7)
Location: fs/utimes.c:236
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81534407)
Location: fs/utimes.c:236
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffff8000103d0bc0)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__arm64_sys_utime32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_utime32(long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c05ac0a0)
Location: fs/utimes.c:225
Inline: False
```
**Symbols:**

```
c05ac0a0-c05ac1bc: __se_sys_utime32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_utime32(long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d38e0)
Location: fs/utimes.c:225
Inline: False
```
**Symbols:**

```
c0000000004d38e0-c0000000004d3a84: __se_sys_utime32 (STB_GLOBAL)
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
In fs/utimes.c (ffffffff81312387)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81302f97)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81310177)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
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
In fs/utimes.c (ffffffff81321977)
Location: fs/utimes.c:225
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utime32
  - fs/utimes.c:__x64_sys_utime32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
