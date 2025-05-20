# Function: <code>callthunks_patch_module_calls</code>

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
void callthunks_patch_module_calls(struct callthunk_sites *cs, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:329
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8205473b-ffffffff82054750: callthunks_patch_module_calls.cold (STB_LOCAL)
ffffffff810bf270-ffffffff810bf317: callthunks_patch_module_calls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void callthunks_patch_module_calls(struct callthunk_sites *cs, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:329
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff820d2d49-ffffffff820d2d5e: callthunks_patch_module_calls.cold (STB_LOCAL)
ffffffff810c2930-ffffffff810c29d7: callthunks_patch_module_calls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void callthunks_patch_module_calls(struct callthunk_sites *cs, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: arch/x86/kernel/callthunks.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff821adbab-ffffffff821adbc0: callthunks_patch_module_calls.cold (STB_LOCAL)
ffffffff810c9da0-ffffffff810c9e47: callthunks_patch_module_calls (STB_GLOBAL)
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
