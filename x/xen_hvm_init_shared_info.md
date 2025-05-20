# Function: <code>xen_hvm_init_shared_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff818180b0)
Location: arch/x86/xen/enlighten.c:1736
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff818180b0-ffffffff818181a8: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81891b90)
Location: arch/x86/xen/enlighten.c:1756
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81891b90-ffffffff81891c9e: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff818c64a0)
Location: arch/x86/xen/enlighten.c:1761
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff818c64a0-ffffffff818c65ba: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101b9a0)
Location: arch/x86/xen/enlighten_hvm.c:27
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101b9a0-ffffffff8101ba0a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c690)
Location: arch/x86/xen/enlighten_hvm.c:28
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101c690-ffffffff8101c6fa: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101d0b0)
Location: arch/x86/xen/enlighten_hvm.c:28
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101d0b0-ffffffff8101d11a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c790)
Location: arch/x86/xen/enlighten_hvm.c:30
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101c790-ffffffff8101c7fa: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101e2c0)
Location: arch/x86/xen/enlighten_hvm.c:30
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101e2c0-ffffffff8101e32a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ec40)
Location: arch/x86/xen/enlighten_hvm.c:30
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ec40-ffffffff8101ecaa: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81021200)
Location: arch/x86/xen/enlighten_hvm.c:31
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81021200-ffffffff8102126a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81021a60)
Location: arch/x86/xen/enlighten_hvm.c:32
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81021a60-ffffffff81021aca: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81023df0)
Location: arch/x86/xen/enlighten_hvm.c:32
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81023df0-ffffffff81023e5a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81028150)
Location: arch/x86/xen/enlighten_hvm.c:32
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81028150-ffffffff810281ba: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8102c6d0)
Location: arch/x86/xen/enlighten_hvm.c:34
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8102c6d0-ffffffff8102c74d: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b5b2)
Location: arch/x86/xen/enlighten_hvm.c:39
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81033780-ffffffff810337fd: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c052)
Location: arch/x86/xen/enlighten_hvm.c:39
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81033710-ffffffff8103378d: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbc12)
Location: arch/x86/xen/enlighten_hvm.c:39
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff81039a10-ffffffff81039a8d: xen_hvm_init_shared_info (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ed70)
Location: arch/x86/xen/enlighten_hvm.c:37
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_map_shared_info
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ed70-ffffffff8101edda: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ec00)
Location: arch/x86/xen/enlighten_hvm.c:30
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ec00-ffffffff8101ec6a: xen_hvm_init_shared_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_hvm_init_shared_info();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ee50)
Location: arch/x86/xen/enlighten_hvm.c:30
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
```
**Symbols:**

```
ffffffff8101ee50-ffffffff8101eeba: xen_hvm_init_shared_info (STB_GLOBAL)
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
