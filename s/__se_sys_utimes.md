# Function: <code>__se_sys_utimes</code>

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
In fs/utimes.c (ffffffff812d3025)
Location: fs/utimes.c:222
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff812e8355)
Location: fs/utimes.c:200
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81306c65)
Location: fs/utimes.c:200
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81319cc5)
Location: fs/utimes.c:198
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81353c45)
Location: fs/utimes.c:200
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81360535)
Location: fs/utimes.c:207
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81366ff5)
Location: fs/utimes.c:208
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff813b5b45)
Location: fs/utimes.c:208
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff8143af65)
Location: fs/utimes.c:208
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff814c9485)
Location: fs/utimes.c:208
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff814ff6c5)
Location: fs/utimes.c:209
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff815342e5)
Location: fs/utimes.c:209
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_utimes(long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (c0000000004d3700)
Location: fs/utimes.c:198
Inline: False
```
**Symbols:**

```
c0000000004d3700-c0000000004d3724: __se_sys_utimes (STB_GLOBAL)
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
In fs/utimes.c (ffffffff813122a5)
Location: fs/utimes.c:198
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81302eb5)
Location: fs/utimes.c:198
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81310095)
Location: fs/utimes.c:198
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
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
In fs/utimes.c (ffffffff81321895)
Location: fs/utimes.c:198
Inline: True
Inline callers:
  - fs/utimes.c:__ia32_sys_utimes
  - fs/utimes.c:__x64_sys_utimes
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
