# Function: <code>free_bprm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212850)
Location: fs/exec.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81212850-ffffffff812128d2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81239330)
Location: fs/exec.c:1348
Inline: False
```
**Symbols:**

```
ffffffff81239330-ffffffff812393b2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c070)
Location: fs/exec.c:1374
Inline: False
```
**Symbols:**

```
ffffffff8124c070-ffffffff8124c0f2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81258180)
Location: fs/exec.c:1401
Inline: False
```
**Symbols:**

```
ffffffff81258180-ffffffff81258202: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a5b0)
Location: fs/exec.c:1412
Inline: False
```
**Symbols:**

```
ffffffff8127a5b0-ffffffff8127a632: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a1120)
Location: fs/exec.c:1426
Inline: False
```
**Symbols:**

```
ffffffff812a1120-ffffffff812a11a2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6120)
Location: fs/exec.c:1430
Inline: False
```
**Symbols:**

```
ffffffff812b6120-ffffffff812b61a2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d2ea0)
Location: fs/exec.c:1431
Inline: False
```
**Symbols:**

```
ffffffff812d2ea0-ffffffff812d2f17: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e49b0)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffffffff812e49b0-ffffffff812e4a27: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131bad0)
Location: fs/exec.c:1552
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffff8131bad0-ffffffff8131bb58: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81326de0)
Location: fs/exec.c:1481
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:do_execveat_common
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff81326de0-ffffffff81326e8b: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132ce80)
Location: fs/exec.c:1478
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff8132ce80-ffffffff8132cf2b: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137a580)
Location: fs/exec.c:1480
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff8137a580-ffffffff8137a62b: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fa2f0)
Location: fs/exec.c:1485
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff813fa2f0-ffffffff813fa39b: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814846d0)
Location: fs/exec.c:1484
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff814846d0-ffffffff814847c2: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b92b0)
Location: fs/exec.c:1487
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff814b92b0-ffffffff814b93a5: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ebaa0)
Location: fs/exec.c:1514
Inline: False
Direct callers:
  - fs/exec.c:kernel_execve
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff814ebaa0-ffffffff814ebb91: free_bprm (STB_LOCAL)
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
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c750)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffff80001038c750-ffff80001038c7e0: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574200)
Location: fs/exec.c:1432
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
c0574200-c057429c: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000483e90)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
c000000000483e90-c000000000483f48: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025d7b6)
Location: fs/exec.c:1432
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffe00025d7b6-ffffffe00025d828: free_bprm (STB_LOCAL)
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
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dcf90)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffffffff812dcf90-ffffffff812dd007: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cdc10)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffffffff812cdc10-ffffffff812cdc87: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dada0)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffffffff812dada0-ffffffff812dae17: free_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_bprm(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ebca0)
Location: fs/exec.c:1432
Inline: False
```
**Symbols:**

```
ffffffff812ebca0-ffffffff812ebd17: free_bprm (STB_LOCAL)
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
