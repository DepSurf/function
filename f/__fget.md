# Function: <code>__fget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229c20)
Location: fs/file.c:693
Inline: False
Direct callers:
  - fs/file.c:fget
  - fs/file.c:SyS_dup
```
**Symbols:**

```
ffffffff81229c20-ffffffff81229ca8: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252380)
Location: fs/file.c:694
Inline: False
Direct callers:
  - fs/file.c:SyS_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff81252380-ffffffff81252408: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812655f0)
Location: fs/file.c:694
Inline: False
Direct callers:
  - fs/file.c:SyS_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff812655f0-ffffffff81265678: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272d80)
Location: fs/file.c:680
Inline: False
Direct callers:
  - fs/file.c:SyS_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff81272d80-ffffffff81272df6: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812956b0)
Location: fs/file.c:683
Inline: False
Direct callers:
  - fs/file.c:SyS_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff812956b0-ffffffff8129572d: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bb830)
Location: fs/file.c:679
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff812bb830-ffffffff812bb8ac: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0a20)
Location: fs/file.c:709
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
```
**Symbols:**

```
ffffffff812d0a20-ffffffff812d0a9c: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eda50)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff812eda50-ffffffff812edac2: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff510)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff812ff510-ffffffff812ff582: __fget (STB_LOCAL)
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
In fs/file.c (ffffffff81339b75)
Location: fs/file.c:740
Inline: True
Inline callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
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
In fs/file.c (ffffffff81344c95)
Location: fs/file.c:840
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
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
In fs/file.c (ffffffff8134ae59)
Location: fs/file.c:852
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
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
In fs/file.c (ffffffff81398bb9)
Location: fs/file.c:912
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
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
In fs/file.c (ffffffff8141af14)
Location: fs/file.c:920
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814a6e93)
Location: fs/file.c:920
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814dbe73)
Location: fs/file.c:921
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff8150edab)
Location: fs/file.c:1043
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:fget
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b0d10)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffff8000103b0d10-ffff8000103b0df8: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590890)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
c0590890-c0590938: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac390)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
c0000000004ac390-c0000000004ac438: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000274db6)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffe000274db6-ffffffe000274e52: __fget (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7af0)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff812f7af0-ffffffff812f7b62: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8710)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff812e8710-ffffffff812e8782: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5900)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff812f5900-ffffffff812f5972: __fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *__fget(unsigned int fd, fmode_t mask, unsigned int refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813072b0)
Location: fs/file.c:710
Inline: False
Direct callers:
  - fs/file.c:ksys_dup
  - fs/file.c:fget
  - fs/file.c:fget_many
```
**Symbols:**

```
ffffffff813072b0-ffffffff81307342: __fget (STB_LOCAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int refs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
