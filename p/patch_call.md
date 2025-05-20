# Function: <code>patch_call</code>

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
void patch_call(void *addr, const struct core_text *ct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810beed0)
Location: arch/x86/kernel/callthunks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_setup
  - arch/x86/kernel/callthunks.c:callthunks_setup
```
**Symbols:**

```
ffffffff810beed0-ffffffff810befe0: patch_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void patch_call(void *addr, const struct core_text *ct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c25f0)
Location: arch/x86/kernel/callthunks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_setup
  - arch/x86/kernel/callthunks.c:callthunks_setup
```
**Symbols:**

```
ffffffff810c25f0-ffffffff810c2700: patch_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void patch_call(void *addr, const struct core_text *ct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c9a60)
Location: arch/x86/kernel/callthunks.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:callthunks_setup
  - arch/x86/kernel/callthunks.c:callthunks_setup
```
**Symbols:**

```
ffffffff810c9a60-ffffffff810c9b70: patch_call (STB_LOCAL)
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
