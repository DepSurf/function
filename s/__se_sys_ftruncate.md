# Function: <code>__se_sys_ftruncate</code>

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
In fs/open.c (ffffffff81295ea5)
Location: fs/open.c:217
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812aac95)
Location: fs/open.c:206
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812c7475)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812d8e85)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff8130eca5)
Location: fs/open.c:204
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff8131afe5)
Location: fs/open.c:204
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff813210f5)
Location: fs/open.c:205
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff8136e5d5)
Location: fs/open.c:202
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff813ecd25)
Location: fs/open.c:202
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff814752c5)
Location: fs/open.c:202
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff814a9c55)
Location: fs/open.c:203
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff814dad95)
Location: fs/open.c:203
Inline: True
Inline callers:
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffff80001037e208)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_ftruncate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_ftruncate(long int fd, long int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568b5c)
Location: fs/open.c:207
Inline: False
```
**Symbols:**

```
c0568b5c-c0568b90: __se_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_ftruncate(long int fd, long int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473c20)
Location: fs/open.c:207
Inline: False
```
**Symbols:**

```
c000000000473c20-c000000000473c3c: __se_sys_ftruncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_ftruncate(long int fd, long int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253f1e)
Location: fs/open.c:207
Inline: False
```
**Symbols:**

```
ffffffe000253f1e-ffffffe000253f54: __se_sys_ftruncate (STB_GLOBAL)
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
In fs/open.c (ffffffff812d1465)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812c20e5)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812cf275)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
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
In fs/open.c (ffffffff812e0085)
Location: fs/open.c:207
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_ftruncate
  - fs/open.c:__x64_sys_ftruncate
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
