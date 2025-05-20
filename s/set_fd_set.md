# Function: <code>set_fd_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81220c80)
Location: include/linux/poll.h:141
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff81220c80-ffffffff81220ca9: set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812488e0)
Location: include/linux/poll.h:141
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812488e0-ffffffff8124892c: set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125b910)
Location: include/linux/poll.h:141
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8125b910-ffffffff8125b95c: set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81268760)
Location: fs/select.c:375
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff81268760-ffffffff812687a9: set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void *ufdset, long unsigned int *fdset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128b010)
Location: fs/select.c:374
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8128b010-ffffffff8128b059: set_fd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812b3d72)
Location: fs/select.c:373
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812b1a40-ffffffff812b1a85: set_fd_set.part.7 (STB_LOCAL)
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
In fs/select.c (ffffffff812c8fb0)
Location: fs/select.c:398
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812e5a0a)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812e36e0-ffffffff812e3725: set_fd_set.part.0 (STB_LOCAL)
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
In fs/select.c (ffffffff812f73a8)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8132fe78)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8133b7cd)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff81341cb9)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8138f679)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff814107e7)
Location: fs/select.c:401
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8149b4b7)
Location: fs/select.c:401
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff814d076b)
Location: fs/select.c:401
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff815030a7)
Location: fs/select.c:401
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffff8000103a46d4)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
Direct callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffff8000103a1f48-ffff8000103a2084: set_fd_set.part.0 (STB_LOCAL)
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
In fs/select.c (c05862bc)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (c00000000049e360)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffe00026b6ac)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812ef988)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812e05b8)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812ed798)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812fe7a2)
Location: fs/select.c:400
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
