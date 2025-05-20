# Function: <code>virt_efi_set_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4ef0)
Location: drivers/firmware/efi/runtime-wrappers.c:111
Inline: False
```
**Symbols:**

```
ffffffff816d4ef0-ffffffff816d4f68: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff817391f0)
Location: drivers/firmware/efi/runtime-wrappers.c:101
Inline: False
```
**Symbols:**

```
ffffffff817391f0-ffffffff817392d3: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176c3e0)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: True
```
**Symbols:**

```
ffffffff8176c3e0-ffffffff8176c4ee: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a780)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: True
```
**Symbols:**

```
ffffffff8178a780-ffffffff8178a881: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800d70)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: True
```
**Symbols:**

```
ffffffff81800d70-ffffffff81800e9e: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8184a220)
Location: drivers/firmware/efi/runtime-wrappers.c:104
Inline: True
```
**Symbols:**

```
ffffffff8184a220-ffffffff8184a30a: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:250
Inline: False
```
**Symbols:**

```
ffffffff818763b0-ffffffff818764e0: virt_efi_set_time (STB_LOCAL)
ffffffff81877324-ffffffff8187735b: virt_efi_set_time.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff818ba5c0-ffffffff818ba6f1: virt_efi_set_time (STB_LOCAL)
ffffffff818bb7b4-ffffffff818bb7eb: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff818ed060-ffffffff818ed191: virt_efi_set_time (STB_LOCAL)
ffffffff818ee254-ffffffff818ee28b: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c0d30)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: True
```
**Symbols:**

```
ffffffff819c0c00-ffffffff819c0d25: virt_efi_set_time.part.0 (STB_LOCAL)
ffffffff819c1d5b-ffffffff819c1d92: virt_efi_set_time.part.0.cold (STB_LOCAL)
ffffffff819c0d30-ffffffff819c0d6a: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c0d90)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: True
```
**Symbols:**

```
ffffffff819c0c60-ffffffff819c0d85: virt_efi_set_time.part.0 (STB_LOCAL)
ffffffff81c2c9b1-ffffffff81c2c9e8: virt_efi_set_time.part.0.cold (STB_LOCAL)
ffffffff819c0d90-ffffffff819c0dca: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a5f29)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: True
```
**Symbols:**

```
ffffffff819a5f00-ffffffff819a6031: virt_efi_set_time (STB_LOCAL)
ffffffff81c1edce-ffffffff81c1ee05: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a526d9)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: True
```
**Symbols:**

```
ffffffff81a526b0-ffffffff81a527ed: virt_efi_set_time (STB_LOCAL)
ffffffff81d30182-ffffffff81d301bf: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff81bc24a0-ffffffff81bc25e7: virt_efi_set_time (STB_LOCAL)
ffffffff81efc7db-ffffffff81efc818: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:264
Inline: False
```
**Symbols:**

```
ffffffff81d670f0-ffffffff81d6727f: virt_efi_set_time (STB_LOCAL)
ffffffff820a9f4a-ffffffff820a9f5e: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:264
Inline: False
```
**Symbols:**

```
ffffffff81dd2200-ffffffff81dd238f: virt_efi_set_time (STB_LOCAL)
ffffffff8212b2f8-ffffffff8212b30c: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a920)
Location: drivers/firmware/efi/runtime-wrappers.c:358
Inline: True
```
**Symbols:**

```
ffffffff81e8a920-ffffffff81e8a9ce: virt_efi_set_time (STB_LOCAL)
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
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b60390)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffff800010b60390-ffff800010b604e0: virt_efi_set_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f8c0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
c0c3f8c0-c0c3f9f8: virt_efi_set_time (STB_LOCAL)
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
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff8188ec40-ffffffff8188ed71: virt_efi_set_time (STB_LOCAL)
ffffffff8188fe34-ffffffff8188fe6b: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff81847760-ffffffff81847891: virt_efi_set_time (STB_LOCAL)
ffffffff818488e4-ffffffff8184891b: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff818e1ec0-ffffffff818e1ff1: virt_efi_set_time (STB_LOCAL)
ffffffff818e30b4-ffffffff818e30eb: virt_efi_set_time.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_time(efi_time_t *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:262
Inline: False
```
**Symbols:**

```
ffffffff818fe960-ffffffff818fea91: virt_efi_set_time (STB_LOCAL)
ffffffff818ffcf4-ffffffff818ffd2b: virt_efi_set_time.cold (STB_LOCAL)
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
