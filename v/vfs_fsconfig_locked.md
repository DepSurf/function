# Function: <code>vfs_fsconfig_locked</code>

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
In fs/fsopen.c (ffffffff8130bb34)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff8131eb44)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff813589bc)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff8136533c)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff8136bd8c)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff813baa5c)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff814406db)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff814cf5ab)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff815059ef)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffffffff8153a7c3)
Location: fs/fsopen.c:282
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fsconfig
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
In fs/fsopen.c (ffff8000103d6d28)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fsconfig
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
In fs/fsopen.c (c05b0e14)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
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
In fs/fsopen.c (c0000000004db2a0)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
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
In fs/fsopen.c (ffffffe000290c5a)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fsconfig
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
In fs/fsopen.c (ffffffff81317124)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81307d14)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81314bf4)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
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
In fs/fsopen.c (ffffffff81326764)
Location: fs/fsopen.c:216
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
</details>
</li>
</ul>

## Differences
