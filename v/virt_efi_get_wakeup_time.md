# Function: <code>virt_efi_get_wakeup_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4e60)
Location: drivers/firmware/efi/runtime-wrappers.c:124
Inline: False
```
**Symbols:**

```
ffffffff816d4e60-ffffffff816d4eec: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff817390f0)
Location: drivers/firmware/efi/runtime-wrappers.c:111
Inline: False
```
**Symbols:**

```
ffffffff817390f0-ffffffff817391eb: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176c2b0)
Location: drivers/firmware/efi/runtime-wrappers.c:115
Inline: True
```
**Symbols:**

```
ffffffff8176c2b0-ffffffff8176c3d6: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a660)
Location: drivers/firmware/efi/runtime-wrappers.c:115
Inline: True
```
**Symbols:**

```
ffffffff8178a660-ffffffff8178a779: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800c20)
Location: drivers/firmware/efi/runtime-wrappers.c:115
Inline: True
```
**Symbols:**

```
ffffffff81800c20-ffffffff81800d62: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8184a110)
Location: drivers/firmware/efi/runtime-wrappers.c:115
Inline: True
```
**Symbols:**

```
ffffffff8184a110-ffffffff8184a212: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:261
Inline: False
```
**Symbols:**

```
ffffffff81876270-ffffffff818763a6: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818772ed-ffffffff81877324: virt_efi_get_wakeup_time.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff818ba480-ffffffff818ba5b7: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818bb77d-ffffffff818bb7b4: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff818ecf20-ffffffff818ed057: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818ee21d-ffffffff818ee254: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c04e0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: True
```
**Symbols:**

```
ffffffff819c03b0-ffffffff819c04d7: virt_efi_get_wakeup_time.part.0 (STB_LOCAL)
ffffffff819c1c11-ffffffff819c1c48: virt_efi_get_wakeup_time.part.0.cold (STB_LOCAL)
ffffffff819c04e0-ffffffff819c052c: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c1bb0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: True
```
**Symbols:**

```
ffffffff819c1a80-ffffffff819c1ba7: virt_efi_get_wakeup_time.part.0 (STB_LOCAL)
ffffffff81c2cbd7-ffffffff81c2cc0e: virt_efi_get_wakeup_time.part.0.cold (STB_LOCAL)
ffffffff819c1bb0-ffffffff819c1bfc: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a5df3)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: True
```
**Symbols:**

```
ffffffff819a5dc0-ffffffff819a5ef7: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff81c1ed97-ffffffff81c1edce: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a53423)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: True
```
**Symbols:**

```
ffffffff81a533f0-ffffffff81a53533: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff81d303e4-ffffffff81d30421: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff81bc2350-ffffffff81bc249d: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff81efc79e-ffffffff81efc7db: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:275
Inline: False
```
**Symbols:**

```
ffffffff81d66f40-ffffffff81d670d5: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff820a9f36-ffffffff820a9f4a: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:275
Inline: False
```
**Symbols:**

```
ffffffff81dd2050-ffffffff81dd21e5: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff8212b2e4-ffffffff8212b2f8: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a850)
Location: drivers/firmware/efi/runtime-wrappers.c:369
Inline: True
```
**Symbols:**

```
ffffffff81e8a850-ffffffff81e8a906: virt_efi_get_wakeup_time (STB_LOCAL)
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
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b60228)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffff800010b60228-ffff800010b60390: virt_efi_get_wakeup_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f780)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
c0c3f780-c0c3f8c0: virt_efi_get_wakeup_time (STB_LOCAL)
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
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff8188eb00-ffffffff8188ec37: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff8188fdfd-ffffffff8188fe34: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff81847620-ffffffff81847757: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818488ad-ffffffff818488e4: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff818e1d80-ffffffff818e1eb7: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818e307d-ffffffff818e30b4: virt_efi_get_wakeup_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_wakeup_time(efi_bool_t *enabled, efi_bool_t *pending, efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:273
Inline: False
```
**Symbols:**

```
ffffffff818fe820-ffffffff818fe957: virt_efi_get_wakeup_time (STB_LOCAL)
ffffffff818ffcbd-ffffffff818ffcf4: virt_efi_get_wakeup_time.cold (STB_LOCAL)
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
