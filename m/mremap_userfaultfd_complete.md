# Function: <code>mremap_userfaultfd_complete</code>

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
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a53e0)
Location: fs/userfaultfd.c:691
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff812a53e0-ffffffff812a544a: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812c88f0)
Location: fs/userfaultfd.c:735
Inline: False
Direct callers:
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff812c88f0-ffffffff812c895a: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812f1c00)
Location: fs/userfaultfd.c:748
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812f1c00-ffffffff812f1c6a: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813065c0)
Location: fs/userfaultfd.c:753
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff813065c0-ffffffff8130662a: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81327b60)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81327b60-ffffffff81327bd3: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133a940)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8133a940-ffffffff8133a9b3: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813749f0)
Location: fs/userfaultfd.c:764
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813749f0-ffffffff81374a63: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813828a0)
Location: fs/userfaultfd.c:732
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813828a0-ffffffff81382913: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81389920)
Location: fs/userfaultfd.c:732
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81389920-ffffffff81389993: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d6c00)
Location: fs/userfaultfd.c:733
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813d6c00-ffffffff813d6c73: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81460520)
Location: fs/userfaultfd.c:742
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81460520-ffffffff814605b8: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814f03e0)
Location: fs/userfaultfd.c:756
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff814f03e0-ffffffff814f0478: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81527230)
Location: fs/userfaultfd.c:791
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81527230-ffffffff815272c8: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155c000)
Location: fs/userfaultfd.c:788
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff8155c000-ffffffff8155c098: mremap_userfaultfd_complete (STB_GLOBAL)
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
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f99c0)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff8000103f99c0-ffff8000103f9a68: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cd8cc)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c05cd8cc-c05cd96c: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000502100)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c000000000502100-c0000000005021c0: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a8c20)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe0002a8c20-ffffffe0002a8cb0: mremap_userfaultfd_complete (STB_GLOBAL)
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
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81332f20)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81332f20-ffffffff81332f93: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323a70)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81323a70-ffffffff81323ae3: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813309f0)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff813309f0-ffffffff81330a63: mremap_userfaultfd_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mremap_userfaultfd_complete(struct vm_userfaultfd_ctx *vm_ctx, long unsigned int from, long unsigned int to, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81343340)
Location: fs/userfaultfd.c:765
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81343340-ffffffff813433b3: mremap_userfaultfd_complete (STB_GLOBAL)
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
