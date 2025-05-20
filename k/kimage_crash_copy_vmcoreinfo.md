# Function: <code>kimage_crash_copy_vmcoreinfo</code>

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
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111dd20)
Location: kernel/kexec_core.c:485
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111dd20-ffffffff8111ddd9: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81129510)
Location: kernel/kexec_core.c:495
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81129510-ffffffff811295d0: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:495
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811380bb-ffffffff811380e9: kimage_crash_copy_vmcoreinfo.cold.12 (STB_LOCAL)
ffffffff81137460-ffffffff81137504: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811438db-ffffffff81143909: kimage_crash_copy_vmcoreinfo.cold.13 (STB_LOCAL)
ffffffff81142c00-ffffffff81142ca4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:498
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8114ec3b-ffffffff8114ec69: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff8114df30-ffffffff8114dfd4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8115a94b-ffffffff8115a979: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff81159c40-ffffffff81159ce4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8116b72b-ffffffff8116b759: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff8116ae00-ffffffff8116aeb0: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:499
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81be458c-ffffffff81be45ba: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff81167540-ffffffff811675f0: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81bd63ad-ffffffff81bd63db: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff811682d0-ffffffff81168380: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:501
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81cb2c71-ffffffff81cb2c9f: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff8118e010-ffffffff8118e0c0: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:501
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81e63a9c-ffffffff81e63ac0: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff811bd550-ffffffff811bd60d: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811ff540)
Location: kernel/kexec_core.c:501
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811ff540-ffffffff811ff61d: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81214940)
Location: kernel/kexec_core.c:502
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81214940-ffffffff81214a1d: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122c8e0)
Location: kernel/kexec_core.c:490
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8122c8e0-ffffffff8122c9bd: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
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
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c9298)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000101c9298-ffff8000101c93ec: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c04101ec)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
c04101ec-c04102c4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c000000000231ad0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c000000000231ad0-c000000000231bdc: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81152f6b-ffffffff81152f99: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff81152260-ffffffff81152304: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8114628b-ffffffff811462b9: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff81145540-ffffffff811455e4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81150e1b-ffffffff81150e49: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff81150110-ffffffff811501b4: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:500
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8115dc3b-ffffffff8115dc69: kimage_crash_copy_vmcoreinfo.cold (STB_LOCAL)
ffffffff8115cf60-ffffffff8115d004: kimage_crash_copy_vmcoreinfo (STB_GLOBAL)
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
