# Function: <code>__se_compat_sys_statfs</code>

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
In fs/statfs.c (ffffffff812d52b5)
Location: fs/statfs.c:286
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff812ea685)
Location: fs/statfs.c:286
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff813090f5)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff8131c165)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81355e75)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff813627b5)
Location: fs/statfs.c:302
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81369255)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff813b7f55)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__x64_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff8143d795)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff814cc055)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81502295)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81536ee5)
Location: fs/statfs.c:305
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffff8000103d3af8)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__arm64_compat_sys_statfs
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
long int __se_compat_sys_statfs(long int pathname, long int buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6550)
Location: fs/statfs.c:300
Inline: False
```
**Symbols:**

```
c0000000004d6550-c0000000004d6564: __se_compat_sys_statfs (STB_GLOBAL)
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
In fs/statfs.c (ffffffff81314745)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81305355)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81312535)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
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
In fs/statfs.c (ffffffff81323d75)
Location: fs/statfs.c:300
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs
  - fs/statfs.c:__ia32_compat_sys_statfs
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
