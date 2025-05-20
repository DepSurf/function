# Function: <code>do_mprotect_pkey</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811f5220)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_pkey_mprotect
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff811f5220-ffffffff811f555c: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81200050)
Location: mm/mprotect.c:376
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_pkey_mprotect
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff81200050-ffffffff8120033b: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812187f0)
Location: mm/mprotect.c:393
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_pkey_mprotect
  - mm/mprotect.c:SyS_mprotect
```
**Symbols:**

```
ffffffff812187f0-ffffffff81218adb: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8123a270)
Location: mm/mprotect.c:456
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff8123a270-ffffffff8123a559: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8124e3e0)
Location: mm/mprotect.c:457
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff8124e3e0-ffffffff8124e6c9: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81260720)
Location: mm/mprotect.c:458
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81260720-ffffffff81260a0a: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126eeb0)
Location: mm/mprotect.c:486
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff8126eeb0-ffffffff8126f19a: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129f4a0)
Location: mm/mprotect.c:512
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff8129f4a0-ffffffff8129f788: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aa860)
Location: mm/mprotect.c:512
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff812aa860-ffffffff812aabf7: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812afca0)
Location: mm/mprotect.c:512
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff812afca0-ffffffff812b0023: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812f14f0)
Location: mm/mprotect.c:522
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff812f14f0-ffffffff812f188d: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81355180)
Location: mm/mprotect.c:615
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81355180-ffffffff813555fb: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813cf6c0)
Location: mm/mprotect.c:671
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff813cf6c0-ffffffff813cfb71: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81404060)
Location: mm/mprotect.c:689
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81404060-ffffffff81404631: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81430630)
Location: mm/mprotect.c:680
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81430630-ffffffff81430c0b: do_mprotect_pkey (STB_LOCAL)
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
In mm/mprotect.c (ffff800010305a24)
Location: mm/mprotect.c:486
Inline: True
Inline callers:
  - mm/mprotect.c:__arm64_sys_mprotect
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
In mm/mprotect.c (c0523974)
Location: mm/mprotect.c:486
Inline: True
Inline callers:
  - mm/mprotect.c:__se_sys_mprotect
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
In mm/mprotect.c (c0000000003d2fe0)
Location: mm/mprotect.c:486
Inline: True
Inline callers:
  - mm/mprotect.c:__se_sys_mprotect
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
In mm/mprotect.c (ffffffe000211770)
Location: mm/mprotect.c:486
Inline: True
Inline callers:
  - mm/mprotect.c:__se_sys_mprotect
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81267500)
Location: mm/mprotect.c:486
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81267500-ffffffff812677ea: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81259850)
Location: mm/mprotect.c:486
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81259850-ffffffff81259b3a: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812652a0)
Location: mm/mprotect.c:486
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff812652a0-ffffffff8126558a: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81274c50)
Location: mm/mprotect.c:486
Inline: False
Direct callers:
  - mm/mprotect.c:__ia32_sys_pkey_mprotect
  - mm/mprotect.c:__x64_sys_pkey_mprotect
  - mm/mprotect.c:__ia32_sys_mprotect
  - mm/mprotect.c:__x64_sys_mprotect
```
**Symbols:**

```
ffffffff81274c50-ffffffff81274f3a: do_mprotect_pkey (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
