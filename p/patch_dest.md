# Function: <code>patch_dest</code>

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
void *patch_dest(void *dest, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810bec50-ffffffff810bed38: patch_dest (STB_LOCAL)
ffffffff820546e2-ffffffff820546f6: patch_dest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *patch_dest(void *dest, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:184
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810c2370-ffffffff810c2458: patch_dest (STB_LOCAL)
ffffffff820d2cdb-ffffffff820d2cef: patch_dest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *patch_dest(void *dest, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810c97e0-ffffffff810c98c8: patch_dest (STB_LOCAL)
ffffffff821adb3d-ffffffff821adb51: patch_dest.cold (STB_LOCAL)
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
