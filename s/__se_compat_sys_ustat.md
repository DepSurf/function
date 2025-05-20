# Function: <code>__se_compat_sys_ustat</code>

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
In fs/statfs.c (ffffffff812d4f65)
Location: fs/statfs.c:371
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff812ea335)
Location: fs/statfs.c:381
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81308d95)
Location: fs/statfs.c:395
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff8131be05)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff813559b5)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff813622d5)
Location: fs/statfs.c:388
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81368db5)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff813b7ab5)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__x64_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff8143d205)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff814cb9e5)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81501c25)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81536875)
Location: fs/statfs.c:391
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffff8000103d3300)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__arm64_compat_sys_ustat
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
long int __se_compat_sys_ustat(long int dev, long int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6120)
Location: fs/statfs.c:386
Inline: False
```
**Symbols:**

```
c0000000004d6120-c0000000004d6138: __se_compat_sys_ustat (STB_GLOBAL)
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
In fs/statfs.c (ffffffff813143e5)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81304ff5)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff813121d5)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
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
In fs/statfs.c (ffffffff81323a15)
Location: fs/statfs.c:386
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_ustat
  - fs/statfs.c:__ia32_compat_sys_ustat
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
