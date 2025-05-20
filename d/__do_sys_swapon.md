# Function: <code>__do_sys_swapon</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3112
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff8124d130-ffffffff8124e2c0: __do_sys_swapon (STB_LOCAL)
ffffffff8124e71c-ffffffff8124e7b7: __do_sys_swapon.cold.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3090
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81261530-ffffffff81262671: __do_sys_swapon (STB_LOCAL)
ffffffff81262bfc-ffffffff81262c9d: __do_sys_swapon.cold.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3102
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff8127c4a0-ffffffff8127d56d: __do_sys_swapon (STB_LOCAL)
ffffffff8127db1e-ffffffff8127dbed: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff8128bf80-ffffffff8128d007: __do_sys_swapon (STB_LOCAL)
ffffffff8128d5a3-ffffffff8128d657: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3142
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff812bf010-ffffffff812bfaa3: __do_sys_swapon (STB_LOCAL)
ffffffff812c00f7-ffffffff812c010d: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3161
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff812cac30-ffffffff812cb65e: __do_sys_swapon (STB_LOCAL)
ffffffff81be8819-ffffffff81be882f: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3132
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff812d1710-ffffffff812d2200: __do_sys_swapon (STB_LOCAL)
ffffffff81bda810-ffffffff81bda826: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3127
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81316e10-ffffffff81317a76: __do_sys_swapon (STB_LOCAL)
ffffffff81cbeca9-ffffffff81cbecf6: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2982
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81382430-ffffffff813830d0: __do_sys_swapon (STB_LOCAL)
ffffffff81e70e61-ffffffff81e70ee2: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2984
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff813fc380-ffffffff813fd074: __do_sys_swapon (STB_LOCAL)
ffffffff82065c53-ffffffff82065c83: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2975
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff8142f690-ffffffff81430376: __do_sys_swapon (STB_LOCAL)
ffffffff820e53e5-ffffffff820e5415: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2980
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81469270-ffffffff81469e0a: __do_sys_swapon (STB_LOCAL)
ffffffff821c2573-ffffffff821c25be: __do_sys_swapon.cold (STB_LOCAL)
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
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010327698)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__arm64_sys_swapon
```
**Symbols:**

```
ffff800010327698-ffff8000103286b8: __do_sys_swapon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053eaec)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__se_sys_swapon
```
**Symbols:**

```
c053eaec-c053fc0c: __do_sys_swapon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fe330)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__se_sys_swapon
```
**Symbols:**

```
c0000000003fe330-c0000000003ff990: __do_sys_swapon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe00022759a)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__se_sys_swapon
```
**Symbols:**

```
ffffffe00022759a-ffffffe0002284ce: __do_sys_swapon (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81284560-ffffffff812855e7: __do_sys_swapon (STB_LOCAL)
ffffffff81285b83-ffffffff81285c37: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff812763d0-ffffffff81277457: __do_sys_swapon (STB_LOCAL)
ffffffff812779f3-ffffffff81277aa7: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81282370-ffffffff812833f7: __do_sys_swapon (STB_LOCAL)
ffffffff81283993-ffffffff81283a47: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __do_sys_swapon(const char *specialfile, int swap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:3098
Inline: False
Direct callers:
  - mm/swapfile.c:__ia32_sys_swapon
  - mm/swapfile.c:__x64_sys_swapon
```
**Symbols:**

```
ffffffff81292060-ffffffff812930d3: __do_sys_swapon (STB_LOCAL)
ffffffff81293684-ffffffff81293738: __do_sys_swapon.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
