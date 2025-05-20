# Function: <code>kernel_get_mempolicy</code>

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
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125af10)
Location: mm/mempolicy.c:1470
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8125af10-ffffffff8125b64d: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f6d0)
Location: mm/mempolicy.c:1510
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8126f6d0-ffffffff8126fee8: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128acb0)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8128acb0-ffffffff8128b4fa: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a820)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff8129a820-ffffffff8129b06a: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ce270)
Location: mm/mempolicy.c:1625
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812ce270-ffffffff812ce337: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9200)
Location: mm/mempolicy.c:1601
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812d9200-ffffffff812d92c7: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0a00)
Location: mm/mempolicy.c:1615
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812e0a00-ffffffff812e0b57: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327cf0)
Location: mm/mempolicy.c:1610
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81327cf0-ffffffff81327ec3: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81396ee0)
Location: mm/mempolicy.c:1674
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81396ee0-ffffffff813970d3: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81416a80)
Location: mm/mempolicy.c:1689
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81416a80-ffffffff81416b69: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81449fb0)
Location: mm/mempolicy.c:1700
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81449fb0-ffffffff8144a0a6: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483a40)
Location: mm/mempolicy.c:1684
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81483a40-ffffffff81483b36: kernel_get_mempolicy (STB_LOCAL)
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
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff8000103393c8)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_sys_get_mempolicy
```
**Symbols:**

```
ffff8000103393c8-ffff800010339c74: kernel_get_mempolicy (STB_LOCAL)
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
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413c80)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/mempolicy.c:__se_sys_get_mempolicy
```
**Symbols:**

```
c000000000413c80-c000000000414490: kernel_get_mempolicy (STB_LOCAL)
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
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292e00)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81292e00-ffffffff8129364a: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284a10)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81284a10-ffffffff8128525a: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290c10)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff81290c10-ffffffff8129145a: kernel_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_get_mempolicy(int *policy, long unsigned int *nmask, long unsigned int maxnode, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a0a40)
Location: mm/mempolicy.c:1556
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:__ia32_sys_get_mempolicy
  - mm/mempolicy.c:__x64_sys_get_mempolicy
```
**Symbols:**

```
ffffffff812a0a40-ffffffff812a1268: kernel_get_mempolicy (STB_LOCAL)
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
