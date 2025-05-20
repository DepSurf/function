# Function: <code>kernel_set_mempolicy</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125ac90)
Location: mm/mempolicy.c:1344
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8125ac90-ffffffff8125ad27: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f450)
Location: mm/mempolicy.c:1384
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8126f450-ffffffff8126f4e7: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128aa30)
Location: mm/mempolicy.c:1430
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8128aa30-ffffffff8128aac7: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a5a0)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff8129a5a0-ffffffff8129a637: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cdb40)
Location: mm/mempolicy.c:1503
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812cdb40-ffffffff812cdbd7: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8a80)
Location: mm/mempolicy.c:1479
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812d8a80-ffffffff812d8b17: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0160)
Location: mm/mempolicy.c:1493
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812e0160-ffffffff812e01f7: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327660)
Location: mm/mempolicy.c:1488
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81327660-ffffffff81327705: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81396730)
Location: mm/mempolicy.c:1552
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81396730-ffffffff813967ef: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81416060)
Location: mm/mempolicy.c:1567
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81416060-ffffffff8141611f: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81449760)
Location: mm/mempolicy.c:1578
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81449760-ffffffff8144981f: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814831e0)
Location: mm/mempolicy.c:1564
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff814831e0-ffffffff8148329f: kernel_set_mempolicy (STB_LOCAL)
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
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010339000)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_sys_set_mempolicy
```
**Symbols:**

```
ffff800010339000-ffff8000103390b4: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413910)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__se_compat_sys_set_mempolicy
  - mm/mempolicy.c:__se_sys_set_mempolicy
```
**Symbols:**

```
c000000000413910-c000000000413a10: kernel_set_mempolicy (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292b80)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81292b80-ffffffff81292c17: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284790)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81284790-ffffffff81284827: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290990)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff81290990-ffffffff81290a27: kernel_set_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int kernel_set_mempolicy(int mode, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a07c0)
Location: mm/mempolicy.c:1434
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__ia32_sys_set_mempolicy
  - mm/mempolicy.c:__x64_sys_set_mempolicy
```
**Symbols:**

```
ffffffff812a07c0-ffffffff812a0857: kernel_set_mempolicy (STB_LOCAL)
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
