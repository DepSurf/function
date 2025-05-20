# Function: <code>efi_call_rts</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81876690)
Location: drivers/firmware/efi/runtime-wrappers.c:166
Inline: False
```
**Symbols:**

```
ffffffff81876690-ffffffff81876d3a: efi_call_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff818ba8d0-ffffffff818bb1c2: efi_call_rts (STB_LOCAL)
ffffffff818bb83c-ffffffff818bb857: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff818ed370-ffffffff818edc62: efi_call_rts (STB_LOCAL)
ffffffff818ee2dc-ffffffff818ee2f7: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff819c0e00-ffffffff819c16c6: efi_call_rts (STB_LOCAL)
ffffffff819c1dac-ffffffff819c1dc7: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff819c1c90-ffffffff819c240e: efi_call_rts (STB_LOCAL)
ffffffff81c2cc28-ffffffff81c2cc43: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff819a6230-ffffffff819a68ff: efi_call_rts (STB_LOCAL)
ffffffff81c1ee56-ffffffff81c1ee71: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff81a535d0-ffffffff81a53c9f: efi_call_rts (STB_LOCAL)
ffffffff81d3043b-ffffffff81d30456: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff81bc27e0-ffffffff81bc3064: efi_call_rts (STB_LOCAL)
ffffffff81efc86f-ffffffff81efc88a: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d67510)
Location: drivers/firmware/efi/runtime-wrappers.c:180
Inline: False
```
**Symbols:**

```
ffffffff81d67510-ffffffff81d67b8b: efi_call_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:180
Inline: False
```
**Symbols:**

```
ffffffff81dd2620-ffffffff81dd2cce: efi_call_rts (STB_LOCAL)
ffffffff8212b320-ffffffff8212b40c: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:216
Inline: False
```
**Symbols:**

```
ffffffff81e8ac50-ffffffff81e8afa4: efi_call_rts (STB_LOCAL)
ffffffff8220d035-ffffffff8220d125: efi_call_rts.cold (STB_LOCAL)
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
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b606f8)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffff800010b606f8-ffff800010b60b64: efi_call_rts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3fc08)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
c0c3fc08-c0c3ffbc: efi_call_rts (STB_LOCAL)
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
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff8188ef50-ffffffff8188f842: efi_call_rts (STB_LOCAL)
ffffffff8188febc-ffffffff8188fed7: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff81847a50-ffffffff818482fb: efi_call_rts (STB_LOCAL)
ffffffff8184896c-ffffffff81848987: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff818e21d0-ffffffff818e2ac2: efi_call_rts (STB_LOCAL)
ffffffff818e313c-ffffffff818e3157: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void efi_call_rts(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:178
Inline: False
```
**Symbols:**

```
ffffffff818fec70-ffffffff818ff6ac: efi_call_rts (STB_LOCAL)
ffffffff818ffd7c-ffffffff818ffd97: efi_call_rts.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
