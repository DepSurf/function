# Function: <code>skip_addr</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool skip_addr(void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810bed50)
Location: arch/x86/kernel/callthunks.c:122
Inline: True
Direct callers:
  - arch/x86/kernel/callthunks.c:is_callthunk
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:call_get_dest
```
**Symbols:**

```
ffffffff810bed50-ffffffff810bedf3: skip_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool skip_addr(void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c2470)
Location: arch/x86/kernel/callthunks.c:122
Inline: True
Direct callers:
  - arch/x86/kernel/callthunks.c:x86_call_depth_emit_accounting
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:call_get_dest
```
**Symbols:**

```
ffffffff810c2470-ffffffff810c2513: skip_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool skip_addr(void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c98e0)
Location: arch/x86/kernel/callthunks.c:117
Inline: True
Direct callers:
  - arch/x86/kernel/callthunks.c:x86_call_depth_emit_accounting
  - arch/x86/kernel/callthunks.c:callthunks_translate_call_dest
  - arch/x86/kernel/callthunks.c:call_get_dest
```
**Symbols:**

```
ffffffff810c98e0-ffffffff810c9983: skip_addr (STB_LOCAL)
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
