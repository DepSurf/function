# Function: <code>do_sys_times</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81094a70)
Location: kernel/sys.c:882
Inline: False
Direct callers:
  - kernel/sys.c:SyS_times
  - kernel/compat.c:compat_SyS_times
```
**Symbols:**

```
ffffffff81094a70-ffffffff81094b13: do_sys_times (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097c80)
Location: kernel/sys.c:882
Inline: False
Direct callers:
  - kernel/sys.c:SyS_times
  - kernel/compat.c:compat_SyS_times
```
**Symbols:**

```
ffffffff81097c80-ffffffff81097d23: do_sys_times (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109cc30)
Location: kernel/sys.c:882
Inline: False
Direct callers:
  - kernel/sys.c:SyS_times
  - kernel/compat.c:compat_SyS_times
```
**Symbols:**

```
ffffffff8109cc30-ffffffff8109ccd3: do_sys_times (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097840)
Location: kernel/sys.c:889
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:SyS_times
```
**Symbols:**

```
ffffffff81097840-ffffffff810978e3: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109e530)
Location: kernel/sys.c:896
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:SyS_times
```
**Symbols:**

```
ffffffff8109e530-ffffffff8109e5d3: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a3870)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810a3870-ffffffff810a3913: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ac480)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810ac480-ffffffff810ac523: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b1a40)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810b1a40-ffffffff810b1ae3: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8110)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810b8110-ffffffff810b81b3: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bfae0)
Location: kernel/sys.c:957
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810bfae0-ffffffff810bfb83: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810baca0)
Location: kernel/sys.c:958
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810baca0-ffffffff810bad43: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bc5d0)
Location: kernel/sys.c:975
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810bc5d0-ffffffff810bc673: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810cefb0)
Location: kernel/sys.c:984
Inline: False
Direct callers:
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810cefb0-ffffffff810cf053: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e7990)
Location: kernel/sys.c:991
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810e7990-ffffffff810e7a4f: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81108660)
Location: kernel/sys.c:992
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff81108660-ffffffff8110871f: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81114970)
Location: kernel/sys.c:1010
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff81114970-ffffffff81114a2f: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111e360)
Location: kernel/sys.c:1010
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff8111e360-ffffffff8111e41f: do_sys_times (STB_LOCAL)
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
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010114318)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_sys_times
```
**Symbols:**

```
ffff800010114318-ffff8000101143b4: do_sys_times (STB_LOCAL)
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
In kernel/sys.c (c036ce60)
Location: kernel/sys.c:943
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_times
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015c3f0)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_sys_times
```
**Symbols:**

```
c00000000015c3f0-c00000000015c4d0: do_sys_times (STB_LOCAL)
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
In kernel/sys.c (ffffffe0000d3c72)
Location: kernel/sys.c:943
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_times
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
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2480)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810b2480-ffffffff810b2523: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a0da0)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810a0da0-ffffffff810a0e43: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b19e0)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810b19e0-ffffffff810b1a83: do_sys_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_sys_times(struct tms *tms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b9dd0)
Location: kernel/sys.c:943
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
**Symbols:**

```
ffffffff810b9dd0-ffffffff810b9e73: do_sys_times (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
