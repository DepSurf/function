# Function: <code>__do_sys_flock</code>

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
In fs/locks.c (ffffffff81300ac1)
Location: fs/locks.c:1994
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff813164b6)
Location: fs/locks.c:2108
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff8133dca6)
Location: fs/locks.c:2126
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff81356296)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff8139d0b6)
Location: fs/locks.c:2218
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff813aea86)
Location: fs/locks.c:2219
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff813b5de6)
Location: fs/locks.c:2222
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff81405ae6)
Location: fs/locks.c:2125
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_flock(unsigned int fd, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:2098
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8147a7b0-ffffffff8147a9e4: __do_sys_flock (STB_LOCAL)
ffffffff81e79a11-ffffffff81e79a25: __do_sys_flock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_flock(unsigned int fd, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:2084
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff8150d1b0-ffffffff8150d3c8: __do_sys_flock (STB_LOCAL)
ffffffff8206ab54-ffffffff8206ab68: __do_sys_flock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_flock(unsigned int fd, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:2061
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81544960-ffffffff81544b7b: __do_sys_flock (STB_LOCAL)
ffffffff820eaac3-ffffffff820eaad7: __do_sys_flock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_flock(unsigned int fd, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/locks.c (0)
Location: fs/locks.c:2068
Inline: False
Direct callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
**Symbols:**

```
ffffffff81579e50-ffffffff8157a06b: __do_sys_flock (STB_LOCAL)
ffffffff821c776d-ffffffff821c7781: __do_sys_flock.cold (STB_LOCAL)
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
In fs/locks.c (ffff800010418dd4)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__arm64_sys_flock
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
In fs/locks.c (c05e537c)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
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
In fs/locks.c (c000000000527f04)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
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
In fs/locks.c (ffffffe0002bfb32)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__se_sys_flock
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
In fs/locks.c (ffffffff8134e876)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff8133f556)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff8134c346)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
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
In fs/locks.c (ffffffff8135eb36)
Location: fs/locks.c:2215
Inline: True
Inline callers:
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
