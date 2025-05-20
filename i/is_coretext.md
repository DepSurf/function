# Function: <code>is_coretext</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_coretext(const struct core_text *ct, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810bebb0)
Location: arch/x86/kernel/callthunks.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810bebb0-ffffffff810bec3e: is_coretext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_coretext(const struct core_text *ct, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c2260)
Location: arch/x86/kernel/callthunks.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810c2260-ffffffff810c2351: is_coretext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_coretext(const struct core_text *ct, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c96d0)
Location: arch/x86/kernel/callthunks.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff810c96d0-ffffffff810c97c1: is_coretext (STB_LOCAL)
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
