# Function: <code>xen_vcpu_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d470)
Location: arch/x86/xen/enlighten.c:244
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101d470-ffffffff8101d545: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c7f0)
Location: arch/x86/xen/enlighten.c:249
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c7f0-ffffffff8101c8eb: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101cf10)
Location: arch/x86/xen/enlighten.c:251
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101cf10-ffffffff8101d012: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019ad0)
Location: arch/x86/xen/enlighten.c:133
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81019ad0-ffffffff81019c9a: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a3b0)
Location: arch/x86/xen/enlighten.c:137
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101a3b0-ffffffff8101a532: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:145
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101b092-ffffffff8101b0ae: xen_vcpu_restore.cold.3 (STB_LOCAL)
ffffffff8101ad80-ffffffff8101aee8: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101b876-ffffffff8101b892: xen_vcpu_restore.cold.3 (STB_LOCAL)
ffffffff8101b550-ffffffff8101b6b8: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101d3ab-ffffffff8101d3c8: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101d070-ffffffff8101d1ef: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101dd4b-ffffffff8101dd68: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101d9f0-ffffffff8101db6f: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8102013b-ffffffff81020158: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101fe30-ffffffff8101ff59: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81bd26a8-ffffffff81bd26c5: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff810208d0-ffffffff810209f9: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81bc491b-ffffffff81bc4938: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff81022c70-ffffffff81022d99: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:151
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81c96ef1-ffffffff81c96f28: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff81026ca0-ffffffff81026e82: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102ae10)
Location: arch/x86/xen/enlighten.c:116
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8102ae10-ffffffff8102afde: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031a70)
Location: arch/x86/xen/enlighten.c:116
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81031a70-ffffffff81031c6b: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81031a70)
Location: arch/x86/xen/enlighten.c:116
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81031a70-ffffffff81031c6b: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037d60)
Location: arch/x86/xen/enlighten.c:119
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff81037d60-ffffffff81037f5b: xen_vcpu_restore (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101dd4b-ffffffff8101dd68: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101d9f0-ffffffff8101db6f: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101dd0b-ffffffff8101dd28: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101d9b0-ffffffff8101db2f: xen_vcpu_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_vcpu_restore();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:147
Inline: False
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
**Symbols:**

```
ffffffff8101df5b-ffffffff8101df78: xen_vcpu_restore.cold (STB_LOCAL)
ffffffff8101dc00-ffffffff8101dd7f: xen_vcpu_restore (STB_GLOBAL)
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
