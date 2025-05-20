# Function: <code>alloc_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122b02a)
Location: fs/file.c:554
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8125378a)
Location: fs/file.c:555
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812669da)
Location: fs/file.c:555
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812741d5)
Location: fs/file.c:541
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff81296ad5)
Location: fs/file.c:542
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812bcc7e)
Location: fs/file.c:537
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812d1f3e)
Location: fs/file.c:537
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812eef76)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff81300a36)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff81339c76)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:470
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
```
**Symbols:**

```
ffffffff81344810-ffffffff8134496e: alloc_fd (STB_LOCAL)
ffffffff81bea732-ffffffff81bea75c: alloc_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:470
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__receive_fd
```
**Symbols:**

```
ffffffff8134ac30-ffffffff8134ad9e: alloc_fd (STB_LOCAL)
ffffffff81bdc76f-ffffffff81bdc791: alloc_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:470
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
```
**Symbols:**

```
ffffffff81398a10-ffffffff81398b7e: alloc_fd (STB_LOCAL)
ffffffff81cc3e1f-ffffffff81cc3e41: alloc_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:499
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
```
**Symbols:**

```
ffffffff8141b250-ffffffff8141b3d0: alloc_fd (STB_LOCAL)
ffffffff81e76722-ffffffff81e76741: alloc_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a72f0)
Location: fs/file.c:499
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
```
**Symbols:**

```
ffffffff814a72f0-ffffffff814a746c: alloc_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc2d0)
Location: fs/file.c:499
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:receive_fd
```
**Symbols:**

```
ffffffff814dc2d0-ffffffff814dc44c: alloc_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_fd(unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e5f0)
Location: fs/file.c:499
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff8150e5f0-ffffffff8150e76c: alloc_fd (STB_LOCAL)
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
In fs/file.c (ffff8000103b29c0)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (c0591ca4)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (c0000000004ae910)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffe0002769fe)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812f9016)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812e9c36)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff812f6e26)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
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
In fs/file.c (ffffffff81308096)
Location: fs/file.c:538
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
