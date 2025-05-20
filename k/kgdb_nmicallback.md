# Function: <code>kgdb_nmicallback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811304c0)
Location: kernel/debug/debug_core.c:743
Inline: False
```
**Symbols:**

```
ffffffff811304c0-ffffffff8113053f: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811387d0)
Location: kernel/debug/debug_core.c:743
Inline: False
```
**Symbols:**

```
ffffffff811387d0-ffffffff8113884f: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81142560)
Location: kernel/debug/debug_core.c:743
Inline: False
```
**Symbols:**

```
ffffffff81142560-ffffffff811425df: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143d80)
Location: kernel/debug/debug_core.c:744
Inline: False
```
**Symbols:**

```
ffffffff81143d80-ffffffff81143dff: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150a40)
Location: kernel/debug/debug_core.c:744
Inline: False
```
**Symbols:**

```
ffffffff81150a40-ffffffff81150abf: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8115f5c0)
Location: kernel/debug/debug_core.c:744
Inline: False
```
**Symbols:**

```
ffffffff8115f5c0-ffffffff8115f63f: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116c300)
Location: kernel/debug/debug_core.c:805
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff8116c300-ffffffff8116c38e: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81179110)
Location: kernel/debug/debug_core.c:805
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81179110-ffffffff811791a3: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81184f60)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81184f60-ffffffff81184ff3: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81198d2b)
Location: kernel/debug/debug_core.c:855
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811990f0-ffffffff81199181: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8119601b)
Location: kernel/debug/debug_core.c:878
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81195e80-ffffffff81195f11: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81196feb)
Location: kernel/debug/debug_core.c:877
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81196e50-ffffffff81196ee6: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c0873)
Location: kernel/debug/debug_core.c:874
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811c0640-ffffffff811c0723: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f3d83)
Location: kernel/debug/debug_core.c:898
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811f3b30-ffffffff811f3c26: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123abc3)
Location: kernel/debug/debug_core.c:886
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8123a950-ffffffff8123aa46: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81251bd3)
Location: kernel/debug/debug_core.c:886
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81251960-ffffffff81251a56: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126ba23)
Location: kernel/debug/debug_core.c:886
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8126b7b0-ffffffff8126b8a6: kgdb_nmicallback (STB_GLOBAL)
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
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fab28)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffff8000101fab28-ffff8000101fabe4: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043ac30)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
c043ac30-c043acf0: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000272660)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - arch/powerpc/kernel/kgdb.c:kgdb_debugger_ipi
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
c000000000272660-c000000000272740: kgdb_nmicallback (STB_GLOBAL)
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
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117d580)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff8117d580-ffffffff8117d613: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811706d0)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff811706d0-ffffffff81170763: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117b350)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff8117b350-ffffffff8117b3e3: kgdb_nmicallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kgdb_nmicallback(int cpu, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81188c70)
Location: kernel/debug/debug_core.c:802
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81188c70-ffffffff81188d03: kgdb_nmicallback (STB_GLOBAL)
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
