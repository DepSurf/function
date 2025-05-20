# Function: <code>__se_compat_sys_lookup_dcookie</code>

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
In fs/dcookies.c (ffffffff81335625)
Location: fs/dcookies.c:212
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff8134c8a5)
Location: fs/dcookies.c:212
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff813752c5)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff8138d545)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff813d8c55)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff813ea855)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In fs/dcookies.c (ffff80001045f6a0)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__arm64_compat_sys_lookup_dcookie
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_lookup_dcookie(long int w0, long int w1, long int buf, long int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcookies.c (c00000000057b520)
Location: fs/dcookies.c:213
Inline: False
```
**Symbols:**

```
c00000000057b520-c00000000057b55c: __se_compat_sys_lookup_dcookie (STB_GLOBAL)
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
In fs/dcookies.c (ffffffff81385b25)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff813765b5)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff813835f5)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
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
In fs/dcookies.c (ffffffff81397115)
Location: fs/dcookies.c:213
Inline: True
Inline callers:
  - fs/dcookies.c:__x32_compat_sys_lookup_dcookie
  - fs/dcookies.c:__ia32_compat_sys_lookup_dcookie
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
