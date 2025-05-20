# Function: <code>userfaultfd_remove</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a5450)
Location: fs/userfaultfd.c:716
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff812a5450-ffffffff812a54f5: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c8960)
Location: fs/userfaultfd.c:760
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff812c8960-ffffffff812c8a05: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1c70)
Location: fs/userfaultfd.c:773
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff812f1c70-ffffffff812f1d17: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81306630)
Location: fs/userfaultfd.c:778
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81306630-ffffffff813066d7: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81327be0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81327be0-ffffffff81327c8a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133a9c0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8133a9c0-ffffffff8133aa6a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81374a70)
Location: fs/userfaultfd.c:789
Inline: False
Direct callers:
  - mm/madvise.c:madvise_remove
```
**Symbols:**

```
ffffffff81374a70-ffffffff81374b4d: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81382920)
Location: fs/userfaultfd.c:757
Inline: False
Direct callers:
  - mm/madvise.c:madvise_remove
```
**Symbols:**

```
ffffffff81382920-ffffffff81382a11: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813899a0)
Location: fs/userfaultfd.c:757
Inline: False
```
**Symbols:**

```
ffffffff813899a0-ffffffff81389a8e: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6c80)
Location: fs/userfaultfd.c:758
Inline: False
```
**Symbols:**

```
ffffffff813d6c80-ffffffff813d6d6b: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814605c0)
Location: fs/userfaultfd.c:767
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff814605c0-ffffffff814606d1: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f0490)
Location: fs/userfaultfd.c:781
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff814f0490-ffffffff814f05a1: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff815272e0)
Location: fs/userfaultfd.c:816
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff815272e0-ffffffff815273f4: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155c0b0)
Location: fs/userfaultfd.c:813
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff8155c0b0-ffffffff8155c1c4: userfaultfd_remove (STB_GLOBAL)
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
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f9a68)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff8000103f9a68-ffff8000103f9b2c: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cd96c)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c05cd96c-c05cda30: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c0000000005021c0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000005021c0-c0000000005022d0: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8cb0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe0002a8cb0-ffffffe0002a8d54: userfaultfd_remove (STB_GLOBAL)
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
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81332fa0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81332fa0-ffffffff8133304a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323af0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81323af0-ffffffff81323b9a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330a70)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81330a70-ffffffff81330b1a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool userfaultfd_remove(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813433c0)
Location: fs/userfaultfd.c:790
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff813433c0-ffffffff8134346a: userfaultfd_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
