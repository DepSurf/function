# Function: <code>callthunks_translate_call_dest</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *callthunks_translate_call_dest(void *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
```
**Symbols:**

```
ffffffff820546f6-ffffffff8205470b: callthunks_translate_call_dest.cold (STB_LOCAL)
ffffffff810bf0c0-ffffffff810bf12d: callthunks_translate_call_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *callthunks_translate_call_dest(void *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
```
**Symbols:**

```
ffffffff820d2cef-ffffffff820d2d04: callthunks_translate_call_dest.cold (STB_LOCAL)
ffffffff810c27e0-ffffffff810c284d: callthunks_translate_call_dest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *callthunks_translate_call_dest(void *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
```
**Symbols:**

```
ffffffff821adb51-ffffffff821adb66: callthunks_translate_call_dest.cold (STB_LOCAL)
ffffffff810c9c50-ffffffff810c9cbd: callthunks_translate_call_dest (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
