# Function: <code>__do_sys_move_mount</code>

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
In fs/namespace.c (ffffffff812f3fde)
Location: fs/namespace.c:3494
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff81305b8e)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff8133f75e)
Location: fs/namespace.c:3578
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff8134b7be)
Location: fs/namespace.c:3600
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff8135206e)
Location: fs/namespace.c:3646
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff813a03de)
Location: fs/namespace.c:3722
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff81423ca6)
Location: fs/namespace.c:3765
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff814b0416)
Location: fs/namespace.c:3871
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_move_mount(int from_dfd, const char *from_pathname, int to_dfd, const char *to_pathname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e5500)
Location: fs/namespace.c:4058
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff814e5500-ffffffff814e56ae: __do_sys_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_move_mount(int from_dfd, const char *from_pathname, int to_dfd, const char *to_pathname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81519330)
Location: fs/namespace.c:4071
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
**Symbols:**

```
ffffffff81519330-ffffffff815194de: __do_sys_move_mount (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b93c0)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_move_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0598314)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_move_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b6650)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_move_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027ca10)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_move_mount
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
In fs/namespace.c (ffffffff812fe16e)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff812eed8e)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff812fbf5e)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
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
In fs/namespace.c (ffffffff8130d2be)
Location: fs/namespace.c:3525
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
