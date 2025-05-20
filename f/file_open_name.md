# Function: <code>file_open_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b4f0)
Location: fs/open.c:971
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff8120b4f0-ffffffff8120b63d: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81231230)
Location: fs/open.c:964
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff81231230-ffffffff81231364: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812437e0)
Location: fs/open.c:981
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812437e0-ffffffff81243914: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124ef40)
Location: fs/open.c:987
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff8124ef40-ffffffff8124f0b9: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81270ec0)
Location: fs/open.c:987
Inline: False
Direct callers:
  - kernel/acct.c:SyS_acct
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff81270ec0-ffffffff81271039: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296b60)
Location: fs/open.c:1029
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff81296b60-ffffffff81296c95: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab800)
Location: fs/open.c:1016
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812ab800-ffffffff812ab935: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c8000)
Location: fs/open.c:1036
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812c8000-ffffffff812c813c: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9a10)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812d9a10-ffffffff812d9b4c: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813101f0)
Location: fs/open.c:1118
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff813101f0-ffffffff81310390: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131c4b0)
Location: fs/open.c:1111
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff8131c4b0-ffffffff8131c650: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81322620)
Location: fs/open.c:1133
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff81322620-ffffffff813227be: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136fb10)
Location: fs/open.c:1151
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff8136fb10-ffffffff8136fcae: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ee460)
Location: fs/open.c:1216
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff813ee460-ffffffff813ee620: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81476ca0)
Location: fs/open.c:1248
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff81476ca0-ffffffff81476e60: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814ab620)
Location: fs/open.c:1345
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff814ab620-ffffffff814ab7a4: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dcac0)
Location: fs/open.c:1342
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/huge_memory.c:split_huge_pages_in_file
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff814dcac0-ffffffff814dcc44: file_open_name (STB_GLOBAL)
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
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037ed70)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:__arm64_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffff80001037ed70-ffff80001037eec0: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569680)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
c0569680-c05697d8: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474af0)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
c000000000474af0-c000000000474ce8: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002549aa)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffe0002549aa-ffffffe000254ad6: file_open_name (STB_GLOBAL)
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
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1ff0)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812d1ff0-ffffffff812d212c: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2c70)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812c2c70-ffffffff812c2dac: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfe00)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812cfe00-ffffffff812cff3c: file_open_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *file_open_name(struct filename *name, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0c10)
Location: fs/open.c:1041
Inline: False
Direct callers:
  - kernel/acct.c:acct_on
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - fs/open.c:filp_open
```
**Symbols:**

```
ffffffff812e0c10-ffffffff812e0d4c: file_open_name (STB_GLOBAL)
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
