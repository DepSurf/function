# Function: <code>virt_efi_get_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4f70)
Location: drivers/firmware/efi/runtime-wrappers.c:98
Inline: False
```
**Symbols:**

```
ffffffff816d4f70-ffffffff816d4ff2: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff817392e0)
Location: drivers/firmware/efi/runtime-wrappers.c:91
Inline: False
```
**Symbols:**

```
ffffffff817392e0-ffffffff817393d1: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176c4f0)
Location: drivers/firmware/efi/runtime-wrappers.c:93
Inline: True
```
**Symbols:**

```
ffffffff8176c4f0-ffffffff8176c60a: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a890)
Location: drivers/firmware/efi/runtime-wrappers.c:93
Inline: True
```
**Symbols:**

```
ffffffff8178a890-ffffffff8178a99b: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800ea0)
Location: drivers/firmware/efi/runtime-wrappers.c:93
Inline: True
```
**Symbols:**

```
ffffffff81800ea0-ffffffff81800fd8: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8184a310)
Location: drivers/firmware/efi/runtime-wrappers.c:93
Inline: True
```
**Symbols:**

```
ffffffff8184a310-ffffffff8184a408: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:239
Inline: False
```
**Symbols:**

```
ffffffff818764e0-ffffffff81876613: virt_efi_get_time (STB_LOCAL)
ffffffff8187735b-ffffffff81877392: virt_efi_get_time.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff818ba700-ffffffff818ba834: virt_efi_get_time (STB_LOCAL)
ffffffff818bb7eb-ffffffff818bb822: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff818ed1a0-ffffffff818ed2d4: virt_efi_get_time (STB_LOCAL)
ffffffff818ee28b-ffffffff818ee2c2: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c0bb0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: True
```
**Symbols:**

```
ffffffff819c0a80-ffffffff819c0ba4: virt_efi_get_time.part.0 (STB_LOCAL)
ffffffff819c1d24-ffffffff819c1d5b: virt_efi_get_time.part.0.cold (STB_LOCAL)
ffffffff819c0bb0-ffffffff819c0bf2: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c0f00)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: True
```
**Symbols:**

```
ffffffff819c0dd0-ffffffff819c0ef4: virt_efi_get_time.part.0 (STB_LOCAL)
ffffffff81c2c9e8-ffffffff81c2ca1f: virt_efi_get_time.part.0.cold (STB_LOCAL)
ffffffff819c0f00-ffffffff819c0f42: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a54de)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: True
```
**Symbols:**

```
ffffffff819a54b0-ffffffff819a55e4: virt_efi_get_time (STB_LOCAL)
ffffffff81c1ec16-ffffffff81c1ec4d: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a5281e)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: True
```
**Symbols:**

```
ffffffff81a527f0-ffffffff81a52930: virt_efi_get_time (STB_LOCAL)
ffffffff81d301bf-ffffffff81d301fc: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff81bc25f0-ffffffff81bc273a: virt_efi_get_time (STB_LOCAL)
ffffffff81efc818-ffffffff81efc855: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:253
Inline: False
```
**Symbols:**

```
ffffffff81d67290-ffffffff81d67422: virt_efi_get_time (STB_LOCAL)
ffffffff820a9f5e-ffffffff820a9f72: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:253
Inline: False
```
**Symbols:**

```
ffffffff81dd23a0-ffffffff81dd2532: virt_efi_get_time (STB_LOCAL)
ffffffff8212b30c-ffffffff8212b320: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a9e0)
Location: drivers/firmware/efi/runtime-wrappers.c:347
Inline: True
```
**Symbols:**

```
ffffffff81e8a9e0-ffffffff81e8aa91: virt_efi_get_time (STB_LOCAL)
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
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b604e0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffff800010b604e0-ffff800010b60638: virt_efi_get_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f9f8)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
c0c3f9f8-c0c3fb34: virt_efi_get_time (STB_LOCAL)
```
</details>
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
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff8188ed80-ffffffff8188eeb4: virt_efi_get_time (STB_LOCAL)
ffffffff8188fe6b-ffffffff8188fea2: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff818478a0-ffffffff818479d4: virt_efi_get_time (STB_LOCAL)
ffffffff8184891b-ffffffff81848952: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff818e2000-ffffffff818e2134: virt_efi_get_time (STB_LOCAL)
ffffffff818e30eb-ffffffff818e3122: virt_efi_get_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_time(efi_time_t *tm, efi_time_cap_t *tc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:251
Inline: False
```
**Symbols:**

```
ffffffff818feaa0-ffffffff818febd4: virt_efi_get_time (STB_LOCAL)
ffffffff818ffd2b-ffffffff818ffd62: virt_efi_get_time.cold (STB_LOCAL)
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
