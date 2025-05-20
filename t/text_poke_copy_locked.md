# Function: <code>text_poke_copy_locked</code>

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
void *text_poke_copy_locked(void *addr, const void *opcode, size_t len, bool core_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105add0)
Location: arch/x86/kernel/alternative.c:1693
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_copy
  - arch/x86/kernel/callthunks.c:patch_dest
```
**Symbols:**

```
ffffffff8105add0-ffffffff8105ae74: text_poke_copy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *text_poke_copy_locked(void *addr, const void *opcode, size_t len, bool core_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105c310)
Location: arch/x86/kernel/alternative.c:1918
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_copy
  - arch/x86/kernel/callthunks.c:patch_dest
```
**Symbols:**

```
ffffffff8105c310-ffffffff8105c3b4: text_poke_copy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *text_poke_copy_locked(void *addr, const void *opcode, size_t len, bool core_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810633d0)
Location: arch/x86/kernel/alternative.c:2008
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_copy
  - arch/x86/kernel/callthunks.c:patch_dest
```
**Symbols:**

```
ffffffff810633d0-ffffffff81063474: text_poke_copy_locked (STB_GLOBAL)
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
