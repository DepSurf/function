# Function: <code>perf_event_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81183fa0)
Location: kernel/events/core.c:6138
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__install_special_mapping
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81183fa0-ffffffff811842e3: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81195c90)
Location: kernel/events/core.c:6734
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81195c90-ffffffff8119605e: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a56e0)
Location: kernel/events/core.c:6832
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811a56e0-ffffffff811a5ac4: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811acdd0)
Location: kernel/events/core.c:7055
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811acdd0-ffffffff811ad233: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c0920)
Location: kernel/events/core.c:7047
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811c0920-ffffffff811c0d86: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e0d20)
Location: kernel/events/core.c:7425
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811e0d20-ffffffff811e1170: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f1180)
Location: kernel/events/core.c:7434
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff811f1180-ffffffff811f15d0: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208990)
Location: kernel/events/core.c:7537
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81208990-ffffffff81208e17: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81215d00)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81215d00-ffffffff81216187: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241f50)
Location: kernel/events/core.c:8204
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81241f50-ffffffff8124203b: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c690)
Location: kernel/events/core.c:8386
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8124c690-ffffffff8124c780: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81250cd0)
Location: kernel/events/core.c:8515
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81250cd0-ffffffff81250dc6: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128ba90)
Location: kernel/events/core.c:8635
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8128ba90-ffffffff8128bb86: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0320)
Location: kernel/events/core.c:8540
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff812e0320-ffffffff812e0454: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81348780)
Location: kernel/events/core.c:8817
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81348780-ffffffff81348862: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81379890)
Location: kernel/events/core.c:8845
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81379890-ffffffff81379975: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a2ba0)
Location: kernel/events/core.c:8915
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff813a2ba0-ffffffff813a2c85: perf_event_mmap (STB_GLOBAL)
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
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029fda0)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffff80001029fda0-ffff8000102a0238: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cfc50)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c04cfc50-c04d0108: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003513e0)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
c0000000003513e0-c0000000003519bc: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cf4d0)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffe0001cf4d0-ffffffe0001cf83e: perf_event_mmap (STB_GLOBAL)
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
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120e350)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8120e350-ffffffff8120e7d7: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201100)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff81201100-ffffffff81201587: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c0f0)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8120c0f0-ffffffff8120c577: perf_event_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_mmap(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121af60)
Location: kernel/events/core.c:7653
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
```
**Symbols:**

```
ffffffff8121af60-ffffffff8121b3f1: perf_event_mmap (STB_GLOBAL)
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
