# Function: <code>compat_set_fd_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263030)
Location: fs/compat.c:1195
Inline: False
Direct callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81263030-ffffffff812630b1: compat_set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f290)
Location: fs/compat.c:1198
Inline: False
Direct callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8128f290-ffffffff8128f309: compat_set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4280)
Location: fs/compat.c:1109
Inline: False
Direct callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff812a4280-ffffffff812a42f9: compat_set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812695dc)
Location: fs/select.c:1173
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128be8c)
Location: fs/select.c:1164
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b2690)
Location: fs/select.c:1165
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812c77a0)
Location: fs/select.c:1177
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812e4332)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812f5d72)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff8132e415)
Location: fs/select.c:1162
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff81339c9b)
Location: fs/select.c:1168
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff81340256)
Location: fs/select.c:1168
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff8138dc26)
Location: fs/select.c:1171
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff8140ef9e)
Location: fs/select.c:1172
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff81499b3e)
Location: fs/select.c:1172
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff814cec0e)
Location: fs/select.c:1172
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff8150154e)
Location: fs/select.c:1172
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffff8000103a2ecc)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (c00000000049cbc0)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812ee352)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812def82)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812ec162)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
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
In fs/select.c (ffffffff812fd15d)
Location: fs/select.c:1152
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
