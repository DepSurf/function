# Function: <code>prepend_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224f80)
Location: fs/dcache.c:2889
Inline: False
Direct callers:
  - fs/dcache.c:d_path
  - fs/dcache.c:__d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:SyS_getcwd
```
**Symbols:**

```
ffffffff81224f80-ffffffff81225211: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b690)
Location: fs/dcache.c:3056
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
**Symbols:**

```
ffffffff8124b690-ffffffff8124b943: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e670)
Location: fs/dcache.c:3066
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
**Symbols:**

```
ffffffff8125e670-ffffffff8125e923: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126bee0)
Location: fs/dcache.c:3096
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
**Symbols:**

```
ffffffff8126bee0-ffffffff8126c19a: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128f7d0)
Location: fs/dcache.c:3108
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
**Symbols:**

```
ffffffff8128f7d0-ffffffff8128fa8a: prepend_path (STB_LOCAL)
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
In fs/d_path.c (ffffffff812d38a0)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff812d38a0-ffffffff812d3b61: prepend_path.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff812e8af0)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff812e8af0-ffffffff812e8db1: prepend_path.isra.3 (STB_LOCAL)
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
In fs/d_path.c (ffffffff81307350)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81307350-ffffffff81307647: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff8131a3b0)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff8131a3b0-ffffffff8131a6b9: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813542f0)
Location: fs/d_path.c:75
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff813542f0-ffffffff813545bb: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81360be0)
Location: fs/d_path.c:75
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81360be0-ffffffff81360ec6: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813676d0)
Location: fs/d_path.c:75
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff813676d0-ffffffff813679a5: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, struct prepend_buffer *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6250)
Location: fs/d_path.c:157
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff813b6250-ffffffff813b6584: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, struct prepend_buffer *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143b820)
Location: fs/d_path.c:155
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff8143b820-ffffffff8143bb29: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, struct prepend_buffer *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814c9e30)
Location: fs/d_path.c:155
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff814c9e30-ffffffff814ca139: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, struct prepend_buffer *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81500070)
Location: fs/d_path.c:156
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81500070-ffffffff81500379: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, struct prepend_buffer *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81534c90)
Location: fs/d_path.c:156
Inline: False
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81534c90-ffffffff81534f99: prepend_path (STB_LOCAL)
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
In fs/d_path.c (ffff8000103d1678)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffff8000103d1678-ffff8000103d1a00: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prepend_path(const struct path *path, const struct path *root, char **buffer, int *buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05ac3bc)
Location: fs/d_path.c:75
Inline: False
Direct callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
c05ac3bc-c05ac740: prepend_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (c0000000004d4050)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
c0000000004d4050-c0000000004d448c: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffe00028cd94)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffe00028cd94-ffffffe00028d078: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff81312990)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81312990-ffffffff81312c99: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff813035a0)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff813035a0-ffffffff813038a9: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff81310780)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81310780-ffffffff81310a89: prepend_path.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/d_path.c (ffffffff81321f80)
Location: fs/d_path.c:75
Inline: True
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
**Symbols:**

```
ffffffff81321f80-ffffffff813222a4: prepend_path.isra.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct prepend_buffer *p</code>
</li>
<li>
<b>Param removed. </b>
<code>char **buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int *buflen</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
</ul>
