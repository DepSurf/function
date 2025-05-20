# Function: <code>__se_sys_fsmount</code>

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
In fs/namespace.c (ffffffff812f3076)
Location: fs/namespace.c:3350
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff81304c36)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff8133eb05)
Location: fs/namespace.c:3434
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff8134ab65)
Location: fs/namespace.c:3456
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff81351395)
Location: fs/namespace.c:3516
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff8139f785)
Location: fs/namespace.c:3593
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff81422c75)
Location: fs/namespace.c:3636
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff814af355)
Location: fs/namespace.c:3742
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff814e42c5)
Location: fs/namespace.c:3929
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff81517fd5)
Location: fs/namespace.c:3943
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffff8000103b84a4)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_fsmount(long int fs_fd, long int flags, long int attr_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0597f70)
Location: fs/namespace.c:3381
Inline: False
```
**Symbols:**

```
c0597f70-c05982bc: __se_sys_fsmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_fsmount(long int fs_fd, long int flags, long int attr_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b5380)
Location: fs/namespace.c:3381
Inline: False
```
**Symbols:**

```
c0000000004b5380-c0000000004b57ac: __se_sys_fsmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_fsmount(long int fs_fd, long int flags, long int attr_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027c70c)
Location: fs/namespace.c:3381
Inline: False
```
**Symbols:**

```
ffffffe00027c70c-ffffffe00027c9ea: __se_sys_fsmount (STB_GLOBAL)
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
In fs/namespace.c (ffffffff812fd216)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff812ede36)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff812fb006)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
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
In fs/namespace.c (ffffffff8130c656)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
