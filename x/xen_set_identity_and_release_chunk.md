# Function: <code>xen_set_identity_and_release_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f61c69)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81f88f2e)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff81fc4322)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff820a4198)
Location: arch/x86/xen/setup.c:252
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826aa87e)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff826d39e3)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82889a83)
Location: arch/x86/xen/setup.c:253
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a0e1a)
Location: arch/x86/xen/setup.c:254
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a3ef2)
Location: arch/x86/xen/setup.c:254
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cca486)
Location: arch/x86/xen/setup.c:255
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff82cca486-ffffffff82cca616: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb62f4)
Location: arch/x86/xen/setup.c:254
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff82fb62f4-ffffffff82fb6484: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff831c088e)
Location: arch/x86/xen/setup.c:254
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff831c088e-ffffffff831c0a1c: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff832a1120)
Location: arch/x86/xen/setup.c:254
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff832a1120-ffffffff832a12ae: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83450146)
Location: arch/x86/xen/setup.c:254
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff83450146-ffffffff834502ce: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83e6c370)
Location: arch/x86/xen/setup.c:255
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff83e6c370-ffffffff83e6c603: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8368ce40)
Location: arch/x86/xen/setup.c:256
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff8368ce40-ffffffff8368d126: xen_set_identity_and_release_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_set_identity_and_release_chunk(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bca00)
Location: arch/x86/xen/setup.c:259
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
**Symbols:**

```
ffffffff838bca00-ffffffff838bcce6: xen_set_identity_and_release_chunk (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82891f18)
Location: arch/x86/xen/setup.c:254
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4ef2)
Location: arch/x86/xen/setup.c:254
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff828a4ec6)
Location: arch/x86/xen/setup.c:254
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
