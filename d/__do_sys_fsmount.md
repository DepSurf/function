# Function: <code>__do_sys_fsmount</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3434
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff8133e7e0-ffffffff8133ead9: __do_sys_fsmount (STB_LOCAL)
ffffffff81341099-ffffffff813410ae: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3456
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff8134a840-ffffffff8134ab39: __do_sys_fsmount (STB_LOCAL)
ffffffff81bea7d2-ffffffff81bea7e7: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3516
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff813510c0-ffffffff8135136b: __do_sys_fsmount (STB_LOCAL)
ffffffff81bdc807-ffffffff81bdc831: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3593
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff8139f480-ffffffff8139f754: __do_sys_fsmount (STB_LOCAL)
ffffffff81cc3fb8-ffffffff81cc3ffa: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3636
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff81422950-ffffffff81422c3f: __do_sys_fsmount (STB_LOCAL)
ffffffff81e768b8-ffffffff81e768f9: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3742
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff814aefe0-ffffffff814af2ff: __do_sys_fsmount (STB_LOCAL)
ffffffff82068cb9-ffffffff82068cce: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3929
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff814e3f40-ffffffff814e4262: __do_sys_fsmount (STB_LOCAL)
ffffffff820e85db-ffffffff820e85f0: __do_sys_fsmount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3943
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
```
**Symbols:**

```
ffffffff81517c70-ffffffff81517f7b: __do_sys_fsmount (STB_LOCAL)
ffffffff821c5335-ffffffff821c534a: __do_sys_fsmount.cold (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b84ac)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
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
In fs/namespace.c (c0597fbc)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
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
In fs/namespace.c (c0000000004b53d4)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
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
In fs/namespace.c (ffffffe00027c732)
Location: fs/namespace.c:3381
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_fsmount
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
