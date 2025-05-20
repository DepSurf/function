# Function: <code>__do_compat_sys_open</code>

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
In fs/open.c (ffffffff81297055)
Location: fs/open.c:1142
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812abd05)
Location: fs/open.c:1109
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812c8515)
Location: fs/open.c:1129
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812d9f25)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff8130fd96)
Location: fs/open.c:1241
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff8131c056)
Location: fs/open.c:1236
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff813221c6)
Location: fs/open.c:1258
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff8136f6b6)
Location: fs/open.c:1276
Inline: True
Inline callers:
  - fs/open.c:__x64_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff813ee215)
Location: fs/open.c:1343
Inline: True
Inline callers:
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff81476965)
Location: fs/open.c:1375
Inline: True
Inline callers:
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff814ab387)
Location: fs/open.c:1471
Inline: True
Inline callers:
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff814dc827)
Location: fs/open.c:1468
Inline: True
Inline callers:
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffff80001037f278)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__arm64_compat_sys_open
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000475200)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__se_compat_sys_open
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
In fs/open.c (ffffffff812d2505)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812c3185)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812d0315)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
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
In fs/open.c (ffffffff812e1145)
Location: fs/open.c:1134
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
```
</details>
</li>
</ul>

## Differences
