# Function: <code>xen_mc_extend_args</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101db30)
Location: arch/x86/xen/multicalls.c:163
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff8101db30-ffffffff8101dcd0: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101ced0)
Location: arch/x86/xen/multicalls.c:163
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8101ced0-ffffffff8101d07f: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101d5f0)
Location: arch/x86/xen/multicalls.c:163
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8101d5f0-ffffffff8101d79f: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101a140)
Location: arch/x86/xen/multicalls.c:163
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8101a140-ffffffff8101a2ca: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101a9e0)
Location: arch/x86/xen/multicalls.c:164
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8101a9e0-ffffffff8101ab73: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101b3e0)
Location: arch/x86/xen/multicalls.c:164
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff8101b3e0-ffffffff8101b567: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff810264a0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff810264a0-ffffffff81026627: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff810281b0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff810281b0-ffffffff81028339: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028ab0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028ab0-ffffffff81028c39: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102aa10)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102aa10-ffffffff8102ab99: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102b2e0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102b2e0-ffffffff8102b440: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102bea0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102bea0-ffffffff8102c00e: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff810306b0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff810306b0-ffffffff81030896: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81035ce0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff81035ce0-ffffffff81035efb: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103da90)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8103da90-ffffffff8103dcd8: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103d940)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8103d940-ffffffff8103db7d: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81043e00)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff81043e00-ffffffff8104403d: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028c10)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028c10-ffffffff81028d99: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028a70)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028a70-ffffffff81028bf9: xen_mc_extend_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct multicall_space xen_mc_extend_args(long unsigned int op, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff810297d0)
Location: arch/x86/xen/multicalls.c:169
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff810297d0-ffffffff810299b1: xen_mc_extend_args (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
