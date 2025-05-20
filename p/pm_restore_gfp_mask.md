# Function: <code>pm_restore_gfp_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192860)
Location: mm/page_alloc.c:158
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81192860-ffffffff811928a3: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a7010)
Location: mm/page_alloc.c:153
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811a7010-ffffffff811a7053: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b73e0)
Location: mm/page_alloc.c:158
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811b73e0-ffffffff811b7441: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bf250)
Location: mm/page_alloc.c:163
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811bf250-ffffffff811bf288: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3d40)
Location: mm/page_alloc.c:166
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811d3d40-ffffffff811d3d93: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5080)
Location: mm/page_alloc.c:165
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811f5080-ffffffff811f50d2: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812073f0)
Location: mm/page_alloc.c:168
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812073f0-ffffffff81207442: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81273a72-ffffffff81273a85: pm_restore_gfp_mask.cold (STB_LOCAL)
ffffffff8126d600-ffffffff8126d638: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127c410)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8127c410-ffffffff8127c449: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae7a0)
Location: mm/page_alloc.c:220
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812ae7a0-ffffffff812ae7d9: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ba3c0)
Location: mm/page_alloc.c:224
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812ba3c0-ffffffff812ba3f9: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf510)
Location: mm/page_alloc.c:234
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812bf510-ffffffff812bf549: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301ed0)
Location: mm/page_alloc.c:241
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81301ed0-ffffffff81301f09: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136a900)
Location: mm/page_alloc.c:245
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8136a900-ffffffff8136a941: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6bf0)
Location: mm/page_alloc.c:304
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff813e6bf0-ffffffff813e6c31: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81191810)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81191810-ffffffff81191851: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811a01d0)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811a01d0-ffffffff811a0211: pm_restore_gfp_mask (STB_GLOBAL)
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
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313e40)
Location: mm/page_alloc.c:219
Inline: False
```
**Symbols:**

```
ffff800010313e40-ffff800010313e90: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052f65c)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
c052f65c-c052f6c4: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e5350)
Location: mm/page_alloc.c:219
Inline: False
```
**Symbols:**

```
c0000000003e5350-c0000000003e53b8: pm_restore_gfp_mask (STB_GLOBAL)
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
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274a60)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81274a60-ffffffff81274a99: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812669d0)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812669d0-ffffffff81266a09: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272800)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81272800-ffffffff81272839: pm_restore_gfp_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_restore_gfp_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812822b0)
Location: mm/page_alloc.c:219
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff812822b0-ffffffff812822e9: pm_restore_gfp_mask (STB_GLOBAL)
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
