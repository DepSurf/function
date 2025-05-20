# Function: <code>__se_compat_sys_statfs64</code>

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
In fs/statfs.c (ffffffff812d5365)
Location: fs/statfs.c:338
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff812ea995)
Location: fs/statfs.c:352
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81309405)
Location: fs/statfs.c:366
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff8131c475)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81356195)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81362ad5)
Location: fs/statfs.c:359
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81369575)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff813b8275)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__x64_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff8143db25)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff814cc495)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff815026d5)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81537325)
Location: fs/statfs.c:362
Inline: True
Inline callers:
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffff8000103d3e10)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__arm64_compat_sys_statfs64
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
long int __se_compat_sys_statfs64(long int pathname, long int sz, long int buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6910)
Location: fs/statfs.c:357
Inline: False
```
**Symbols:**

```
c0000000004d6910-c0000000004d6944: __se_compat_sys_statfs64 (STB_GLOBAL)
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
In fs/statfs.c (ffffffff81314a55)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81305665)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81312845)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
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
In fs/statfs.c (ffffffff81324085)
Location: fs/statfs.c:357
Inline: True
Inline callers:
  - fs/statfs.c:__x32_compat_sys_statfs64
  - fs/statfs.c:__ia32_compat_sys_statfs64
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
