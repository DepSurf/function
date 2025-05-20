# Function: <code>kgdb_nmicallin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81130540)
Location: kernel/debug/debug_core.c:762
Inline: False
```
**Symbols:**

```
ffffffff81130540-ffffffff811305f5: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81138850)
Location: kernel/debug/debug_core.c:762
Inline: False
```
**Symbols:**

```
ffffffff81138850-ffffffff81138905: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811425e0)
Location: kernel/debug/debug_core.c:762
Inline: False
```
**Symbols:**

```
ffffffff811425e0-ffffffff81142695: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143e00)
Location: kernel/debug/debug_core.c:763
Inline: False
```
**Symbols:**

```
ffffffff81143e00-ffffffff81143ec9: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150ac0)
Location: kernel/debug/debug_core.c:763
Inline: False
```
**Symbols:**

```
ffffffff81150ac0-ffffffff81150b89: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8115f640)
Location: kernel/debug/debug_core.c:763
Inline: False
```
**Symbols:**

```
ffffffff8115f640-ffffffff8115f6fd: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116c3b0)
Location: kernel/debug/debug_core.c:826
Inline: False
```
**Symbols:**

```
ffffffff8116c3b0-ffffffff8116c46e: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811791d0)
Location: kernel/debug/debug_core.c:826
Inline: False
```
**Symbols:**

```
ffffffff811791d0-ffffffff81179295: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81185020)
Location: kernel/debug/debug_core.c:823
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81185020-ffffffff811850e5: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81199190)
Location: kernel/debug/debug_core.c:876
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81199190-ffffffff81199251: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81195f20)
Location: kernel/debug/debug_core.c:900
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81195f20-ffffffff81195fe1: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81196ef0)
Location: kernel/debug/debug_core.c:899
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81196ef0-ffffffff81196fb1: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c0730)
Location: kernel/debug/debug_core.c:896
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811c0730-ffffffff811c0833: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f3c30)
Location: kernel/debug/debug_core.c:920
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff811f3c30-ffffffff811f3d42: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123aa60)
Location: kernel/debug/debug_core.c:908
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8123aa60-ffffffff8123ab72: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81251a70)
Location: kernel/debug/debug_core.c:908
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81251a70-ffffffff81251b82: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126b8c0)
Location: kernel/debug/debug_core.c:908
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8126b8c0-ffffffff8126b9d2: kgdb_nmicallin (STB_GLOBAL)
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
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fac20)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
ffff8000101fac20-ffff8000101fad04: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043ad2c)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
c043ad2c-c043ae08: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000272770)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
c000000000272770-c000000000272864: kgdb_nmicallin (STB_GLOBAL)
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
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117d640)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
ffffffff8117d640-ffffffff8117d705: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81170790)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
ffffffff81170790-ffffffff81170855: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117b410)
Location: kernel/debug/debug_core.c:823
Inline: False
```
**Symbols:**

```
ffffffff8117b410-ffffffff8117b4d5: kgdb_nmicallin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kgdb_nmicallin(int cpu, int trapnr, void *regs, int err_code, atomic_t *send_ready);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81188d30)
Location: kernel/debug/debug_core.c:823
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff81188d30-ffffffff81188df5: kgdb_nmicallin (STB_GLOBAL)
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
