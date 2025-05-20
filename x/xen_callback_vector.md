# Function: <code>xen_callback_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9cd0)
Location: drivers/xen/events/events_base.c:1626
Inline: True
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff814c9cd0-ffffffff814c9e65: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a850)
Location: drivers/xen/events/events_base.c:1649
Inline: True
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff8151a850-ffffffff8151a9e6: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546d40)
Location: drivers/xen/events/events_base.c:1644
Inline: True
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81546d40-ffffffff81546eba: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155ab10)
Location: drivers/xen/events/events_base.c:1642
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff8155ab10-ffffffff8155ac8f: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bef30)
Location: drivers/xen/events/events_base.c:1642
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff815bef30-ffffffff815befce: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1640
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff815f766d-ffffffff815f76aa: xen_callback_vector.cold.28 (STB_LOCAL)
ffffffff815f7520-ffffffff815f7592: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81612727)
Location: drivers/xen/events/events_base.c:1640
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81612727-ffffffff8161275a: xen_callback_vector.cold.27 (STB_LOCAL)
ffffffff816125c0-ffffffff8161264b: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81646579)
Location: drivers/xen/events/events_base.c:1649
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81646561-ffffffff81646594: xen_callback_vector.cold (STB_LOCAL)
ffffffff81646310-ffffffff8164639b: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81668a23)
Location: drivers/xen/events/events_base.c:1649
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81668a0b-ffffffff81668a3e: xen_callback_vector.cold (STB_LOCAL)
ffffffff81668890-ffffffff8166891b: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010832958)
Location: drivers/xen/events/events_base.c:1668
Inline: False
```
**Symbols:**

```
ffff800010832958-ffff800010832970: xen_callback_vector (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162e887)
Location: drivers/xen/events/events_base.c:1706
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff8162e86f-ffffffff8162e8a2: xen_callback_vector.cold (STB_LOCAL)
ffffffff8162e6c0-ffffffff8162e74b: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165c863)
Location: drivers/xen/events/events_base.c:1649
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff8165c84b-ffffffff8165c87e: xen_callback_vector.cold (STB_LOCAL)
ffffffff8165c6d0-ffffffff8165c75b: xen_callback_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_callback_vector();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676e53)
Location: drivers/xen/events/events_base.c:1649
Inline: True
Direct callers:
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff81676e3b-ffffffff81676e6e: xen_callback_vector.cold (STB_LOCAL)
ffffffff81676cc0-ffffffff81676d4b: xen_callback_vector (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
