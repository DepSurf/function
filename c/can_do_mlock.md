# Function: <code>can_do_mlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff811c2c30)
Location: mm/mlock.c:27
Inline: True
Inline callers:
  - mm/mlock.c:do_mlock
  - mm/mlock.c:SyS_mlockall
Direct callers:
  - mm/mlock.c:do_mlock
  - mm/mlock.c:SyS_mlockall
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811c2c30-ffffffff811c2c48: can_do_mlock.part.9 (STB_LOCAL)
ffffffff811c2c50-ffffffff811c2c82: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff811df9ca)
Location: mm/mlock.c:27
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811de7d0-ffffffff811de7e5: can_do_mlock.part.10 (STB_LOCAL)
ffffffff811de7f0-ffffffff811de822: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff811ef92a)
Location: mm/mlock.c:27
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811ee5f0-ffffffff811ee605: can_do_mlock.part.11 (STB_LOCAL)
ffffffff811ee610-ffffffff811ee642: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff811fa83a)
Location: mm/mlock.c:28
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff811f9590-ffffffff811f95a5: can_do_mlock.part.11 (STB_LOCAL)
ffffffff811f95b0-ffffffff811f95e2: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff81212d6a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812119c0-ffffffff812119d5: can_do_mlock.part.10 (STB_LOCAL)
ffffffff812119e0-ffffffff81211a13: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff81233d66)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81232710-ffffffff81232725: can_do_mlock.part.14 (STB_LOCAL)
ffffffff81232730-ffffffff81232763: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff81247336)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81245f50-ffffffff81245f65: can_do_mlock.part.14 (STB_LOCAL)
ffffffff81245f70-ffffffff81245fa3: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff8125954a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81258100-ffffffff81258115: can_do_mlock.part.0 (STB_LOCAL)
ffffffff81258120-ffffffff81258152: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff81267a1a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812665d0-ffffffff812665e5: can_do_mlock.part.0 (STB_LOCAL)
ffffffff812665f0-ffffffff81266622: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81297b44)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81296740-ffffffff81296777: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a2c06)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812a16c0-ffffffff812a16f7: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a8486)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812a6e80-ffffffff812a6eb7: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e9ac6)
Location: mm/mlock.c:30
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff812e8350-ffffffff812e8387: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81349eb2)
Location: mm/mlock.c:40
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81349710-ffffffff81349757: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c29d2)
Location: mm/mlock.c:40
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff813c1a10-ffffffff813c1a57: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813f7c12)
Location: mm/mlock.c:40
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff813f6890-ffffffff813f68d7: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff814237e2)
Location: mm/mlock.c:40
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81422540-ffffffff81422587: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffff8000102feb7c)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffff8000102fd548-ffff8000102fd568: can_do_mlock.part.0 (STB_LOCAL)
ffff8000102fd568-ffff8000102fd59c: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (c051db88)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
c051ca44-c051ca64: can_do_mlock.part.0 (STB_LOCAL)
c051ca64-c051caa8: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (c0000000003ca770)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
c0000000003c88e0-c0000000003c8918: can_do_mlock.part.0 (STB_LOCAL)
c0000000003c8920-c0000000003c8954: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffe00020ce44)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffe00020bf1a-ffffffe00020bf3e: can_do_mlock.part.0 (STB_LOCAL)
ffffffe00020bf3e-ffffffe00020bf6c: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff8126006a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8125ec20-ffffffff8125ec35: can_do_mlock.part.0 (STB_LOCAL)
ffffffff8125ec40-ffffffff8125ec72: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff8125248a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81251050-ffffffff81251065: can_do_mlock.part.0 (STB_LOCAL)
ffffffff81251070-ffffffff812510a2: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff8125de0a)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8125c9c0-ffffffff8125c9d5: can_do_mlock.part.0 (STB_LOCAL)
ffffffff8125c9e0-ffffffff8125ca12: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_do_mlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff8126d7ea)
Location: mm/mlock.c:29
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8126c3a0-ffffffff8126c3b5: can_do_mlock.part.0 (STB_LOCAL)
ffffffff8126c3c0-ffffffff8126c3f2: can_do_mlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
